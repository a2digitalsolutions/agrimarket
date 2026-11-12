# AgriMarket

Piattaforma digitale in cui i produttori italiani di olio, mandorle, pistacchi, frutta secca e frutta pubblicano i loro prodotti e gli acquirenti li trovano e li comprano, vedendo subito il prezzo totale con la spedizione inclusa.

Stato: idea in fase di definizione (documento del 12 novembre 2026). Non esiste ancora codice.

## L'idea

- Il produttore pubblica il prodotto, la quantità minima e il prezzo al kg (o al litro).
- L'acquirente cerca, trova e compra direttamente sulla piattaforma.
- La piattaforma si collega ai servizi di spedizione e calcola il costo di consegna in tempo reale.
- L'acquirente vede un unico prezzo finale, spedizione inclusa.
- Ricavo della piattaforma: una commissione sull'incasso del produttore (ipotesi iniziale 5%, vedi "Stima dei guadagni").

## Posizionamento scelto

Il modello "marketplace generalista dal produttore al consumatore" è già presidiato. AgriMarket si distingue su quattro punti:

1. **Solo prodotti non deperibili all'inizio**: olio, mandorle, pistacchi, frutta secca, conserve. La frutta fresca arriva in una fase successiva, perché richiede consegne rapide e genera rimborsi.
2. **Acquirenti professionali piccoli**: pasticcerie, gelaterie, ristoranti, gastronomie e negozi che comprano 5-50 kg per ordine. Sono troppo piccoli per l'ingrosso tradizionale.
3. **Prezzo al kg con quantità minima e spedizione inclusa**: oggi questi acquirenti chiedono preventivi per telefono.
4. **Partenza da una sola regione** (Sicilia), per avere un catalogo credibile con 30-40 produttori.

In sintesi: l'ingrosso digitale dell'olio e della frutta secca siciliani per piccoli professionisti italiani ed europei.

Secondo pubblico: privati che comprano in quantità (latte di olio da 3-5 litri, mandorle a chili), in particolare italiani all'estero e gruppi d'acquisto.

## Concorrenti

| Nome | Tipo | Cosa fa | Differenza rispetto ad AgriMarket |
|---|---|---|---|
| CrowdFarming | B2C, Europa | Vendita diretta dall'agricoltore al consumatore (frutta, verdura, olio, frutta secca), con hub logistici propri. Dichiara circa 10.000 produttori e 2 milioni di utenti. | Rivolto ai privati e al biologico, non ai piccoli professionali |
| OlivYou | B2C, Italia | E-commerce specializzato in olio extravergine, con magazzino proprio vicino a Milano e consegna in Europa | Compra e rivende, solo olio, solo privati |
| Soplaya | B2B, Italia | Marketplace gestito per le forniture dei ristoranti, con logistica propria in alcune città | Consegna locale su città servite, non spedizione dal produttore |
| Sicilus | B2C, Sicilia | Negozio online di prodotti siciliani con spedizione in UE | Negozio tradizionale, non marketplace |
| Nutrada, Tridge, Torg, Alibaba | B2B ingrosso | Vetrine per trovare fornitori e chiedere preventivi | Nessun acquisto immediato, volumi grandi |

## Stima dei guadagni

Ipotesi di lavoro, non dati di mercato:

- ordine medio di 250 € di merce;
- costo del pagamento con carta a carico della piattaforma, circa 4,30 € a ordine;
- netto per ordine: circa 8,20 € con commissione al 5%, circa 20,70 € al 10%.

| Scenario | Clienti attivi | Ordini l'anno | Vendite dei produttori | Netto al 5% | Netto al 10% |
|---|---|---|---|---|---|
| Prudente | 50 | 300 | 75.000 € | circa 2.500 € | circa 6.200 € |
| Realistico | 300 | 2.400 | 600.000 € | circa 19.700 € | circa 49.700 € |
| Ottimistico | 1.500 | 15.000 | 3.750.000 € | circa 123.000 € | circa 310.000 € |

Il netto è prima di pubblicità, assistenza clienti, rimborsi e costi tecnici.

Al 5% un cliente che ordina 8 volte l'anno vale circa 65 € l'anno: il costo per acquisirlo deve restare sotto i 50-60 €. **Decisione aperta:** alzare la commissione al 10%, oppure tenere il 5% al produttore e aggiungere una quota di servizio all'acquirente.

## Piano di marketing

### Piccoli professionali

1. **Contatto diretto**: liste di pasticcerie, gelaterie e gastronomie città per città, contattate per telefono o di persona con l'offerta di un campione. L'email a freddo richiede il consenso anche verso le aziende.
2. **Google Ads sulle ricerche d'acquisto**: ad esempio "pasta di pistacchio ingrosso", "mandorle sgusciate prezzo al kg".
3. **Instagram e Facebook**: pubblicità mirata per interessi professionali e presenza nei gruppi di categoria.
4. **Fiere di settore**: Sigep di Rimini (gelateria e pasticceria).
5. **Passaparola incentivato**: sconto sul prossimo ordine a chi porta un collega.

### Privati che comprano in quantità

- Campagna concentrata tra ottobre e dicembre sull'olio nuovo in latte da 3 e 5 litri.
- Google Shopping e ricerca, ad esempio "olio nuovo siciliano 5 litri".
- Pubblicità su Facebook e Instagram verso chi parla italiano in Germania, Svizzera, Belgio e Francia.
- Gruppi d'acquisto (GAS, condomini, colleghi) che fanno un ordine collettivo.

## Rischi e vincoli

- **Avvio del marketplace**: i produttori non pubblicano senza acquirenti e viceversa. È il costo principale, più del software.
- **Pagamenti**: la piattaforma non può incassare e poi girare i soldi al produttore senza una licenza da istituto di pagamento. Serve un servizio che divide il pagamento in automatico (ad esempio Stripe Connect).
- **Spedizioni**: i comparatori (Packlink, Sendcloud, Paccofacile) offrono il prezzo in tempo reale via API per i pacchi; gli ordini grandi su pallet richiedono preventivi diversi.
- **Qualità e contestazioni**: serve una regola chiara su chi rimborsa in caso di merce danneggiata o non conforme.
- **Margine**: al 5% il margine per ordine è molto basso (vedi sopra).

## Prossimi passi

1. Validazione manuale: chiudere a mano dieci vendite tra produttori siciliani e pasticcerie o gelaterie, prima di scrivere codice.
2. Decidere la commissione (5%, 10% o quota mista).
3. Definire il budget pubblicitario dei primi tre mesi.
4. Preparare i testi degli annunci e il messaggio di primo contatto per i professionali.
5. Definire le funzioni della prima versione della piattaforma.

## Fonti

- [Euronews – CrowdFarming](https://it.euronews.com/2026/06/05/crowdfarming-la-piattaforma-che-vuole-nutrire-meglio-leuropa)
- [StartupItalia – OlivYou](https://startupitalia.eu/79109-20211022-olivyou)
- [EconomyUp – Soplaya](https://www.economyup.it/food/125-milioni-per-il-marketplace-b2b-della-startup-foodtech-soplaya/)
- [Sicilus](https://sicilus.com/en/products/cutrera-igp-sicilia-extra-virgin-olive-oil-250-ml)
- [Nutrada](https://nutrada.com/it/blog/nutrada-la-nuova-piattaforma-di-commercio-b2b-alimentare)
- [ICE – Business Opportunities](https://www.ice.it/en/my-home/business-opportunities/details/2942)
