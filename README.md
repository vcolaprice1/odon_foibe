# 🗺️ Mappa degli odonimi relativi ai massacri delle foibe in Italia

Questa mappa interattiva consente di esplorare la diffusione e localizzazione nel territorio italiano degli odonimi relativi ai massacri delle foibe. La toponomastica è uno strumento centrale nella costruzione della memoria pubblica e nel caso della memoria delle foibe ha assunto un ruolo rilevante fin da prima dell’istituzione del Giorno del Ricordo nel 2004.

La rilevazione è stata effettuata in data 4 gennaio 2025.

📍 La mappa è consultabile qui:  
🔗 [https://vcolaprice1.github.io/odon_foibe/](https://vcolaprice1.github.io/odon_foibe/)

## 📊 Distribuzione regionale degli odonimi legati alle foibe

| Regione                 | N. odonimi |
|-------------------------|------------|
| Lombardia               | 61         |
| Veneto                  | 57         |
| Puglia                  | 31         |
| Emilia-Romagna          | 28         |
| Piemonte                | 24         |
| Lazio                   | 22         |
| Sicilia                 | 20         |
| Toscana                 | 17         |
| Marche                  | 14         |
| Friuli-Venezia Giulia   | 12         |
| Umbria                  | 12         |
| Abruzzo                 | 11         |
| Liguria                 | 7          |
| Sardegna                | 7          |
| Campania                | 6          |
| Calabria                | 3          |
| Trentino-Alto Adige     | 3          |
| Basilicata              | 0          |
| Molise                  | 0          |
| Valle d'Aosta           | 0          |
| **Totale**              | **335**    |

---

## 🗂️ Dataset

Il file `vie.geojson` contiene:

- nome dell’odonimo;
- descrizione completa;
- comune (estratto automaticamente);
- coordinate geografiche.

Le coordinate e gli indirizzi sono stati estratti da OpenStreetMap. Il dataset è stato reso disponibile e scaricabile in formato CSV su Zenodo 🔗 [https://doi.org/10.5281/zenodo.15647533](https://doi.org/10.5281/zenodo.15647533).

---

## 🗺️ Come usare la mappa

- Cliccando su ciascun punto puoi accedere al **nome dell’odonimo** e alla sua **collocazione**.

---

## ✍️ Approfondimenti

Considerazioni e approfondimenti ulteriori sono disponibili nell’articolo:

Vincenzo Colaprice, "La Puglia nelle foibe: quando la memoria pubblica rinuncia alla ricerca storica", *Farestoria. Società e storia pubblica*, Anno VI, n. 1, 2024, pp. 137-144.

---

## 👤 Autore

Ricerca e sviluppo a cura di [Vincenzo Colaprice](https://www.sissco.it/soci/colaprice-vincenzo/) ([Università degli Studi di Torino](https://www.dipstudistorici.unito.it/do/docenti.pl/Show?_id=vcolapri#tab-profilo)).

---

## 📁 Struttura del repository

- `index.html`
- `data/`
  - `vie.geojson`
  - `regioni.geojson`
