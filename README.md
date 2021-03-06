# Parametric_Builder

### Artioscad parametric builder, made with Power Automate

This script allows everyone to build parametric designs with the help of a workstation running Microsoft Power Automate 

You can simply download [Microsoft Power Automate Desktop ](https://powerautomate.microsoft.com/it-it/desktop/) (it's free), and copy & paste my code into a new, empty flow.
Remember that you need to replace every custom menu/material/parametric design name with your own terms, I tried to highlight them with "REPLACE_WITH_YOUR_SELECTED_XXXXX_NAME".
If I missed something look for every italian or custom term and replace it.


---

# Costruttore di parametrici

### Costruttore di parametrici per ArtiosCAD tramite flusso Power Automate

Grazie a questo flow fatto girare su una workstation tramite Microsoft Power Automate chiunque ha la possibilità di avviare la costruzione di uno specifico Design Parametrico.

Il download di [Microsoft Power Automate Desktop](https://powerautomate.microsoft.com/it-it/desktop/) è gratuito. Dopo aver creato un nuovo flusso, ti basterà copiare e incollare il mio flow per importarlo corrrettamente. Prima di avviarlo controlla e sotituisci le linee di codice con indicato "REPLACE_WITH_YOUR_SELECTED_XXXXX_NAME" con i termini utilizzati dai tuoi menù/libreria materiali/parametrici  ecc ecc. Lavorando con una versione standard di ArtiosCAD 20 in italiano non dovrebbero comparire molti errori ma potrebbe essermi sfuggito qualcosa.

In ogni caso puoi utilizzare il mio flow come semplice riferimento per costruire il tuo.

In breve, grazie all'inserimento delle variabili  L W D (ma se ne possono aggiungere molte altre) e alla scelta del materiale tramite la comparsa di finestre a scelta multipla, qualsiasi utente (soprattutto personale non tecnico e/o abituato all'uso di programmi CAD) può creare facilmente i propri parametrici. 

L'idea alla base di questo flusso nasce dalla volontà di annullare (quando possibile) i tempi morti di attesa fra la richiesta di modelli standardizzati da parte dell'ufficio commerciale e l'effettiva ricezione/inizio della lavorazione da parte dell'ufficio tecnico oberato di altri impegni o occupato da lunghe lavorazioni. 

ATTENZIONE: lo stesso risultato si può ottenere impostando un flusso Esko AE che parta da un'esportazione XML inviata da un utente X tramite l'ERP aziendale
