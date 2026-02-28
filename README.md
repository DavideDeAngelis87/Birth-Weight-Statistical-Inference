# Statistical Modeling & Inference: Neonatal Weight Prediction (R)

## Descrizione del Progetto
Creare un modello statistico in grado di prevedere con precisione il peso dei neonati alla nascita, basandosi su variabili cliniche raccolte da tre ospedali. Il progetto mira a migliorare la gestione delle gravidanze ad alto rischio, ottimizzare le risorse ospedaliere e garantire migliori risultati per la salute neonatale. Il progetto si inserisce all'interno di un contesto di crescente attenzione verso la prevenzione delle complicazioni neonatali. La possibilità di prevedere il peso alla nascita dei neonati rappresenta un'opportunità fondamentale per migliorare la pianificazione clinica e ridurre i rischi associati a nascite problematiche, come parti prematuri o neonati con basso peso

## Struttura dell'Analisi
Il workflow analitico segue un approccio scientifico suddiviso in fasi chiave:

1.  **Analisi Esplorativa (EDA):** studio della distribuzione dei dati, individuazione di outlier e analisi delle relazioni non lineari tra i predittori.
2.  **Hypothesis Testing:** test statistici come il Chi quadro o il test t per saggiare alcune delle dimensioni fondamentali del campione
3.  **Modellazione Statistica:** implementazione di un modello di **Regressione Lineare Multipla** per stimare il peso neonatale basandosi su variabili quali età della madre, abitudine al fumo, peso pregravidico e settimane di gestazione.
4.  **Feature Selection:** ottimizzazione del modello per bilanciare complessità e capacità predittiva (R-squared).
5.  **Diagnostica del Modello:** verifica puntuale delle assunzioni della regressione (normalità dei residui, omoschedasticità e controllo della multicollinearità tramite VIF).


## Tech Stack & Competenze
* **Linguaggio:** R
* **Librerie principali:** `tidyverse`, `broom`, `GGally`, `ggplot2`.


## Risultati Chiave
- **Identificazione Fattori di Rischio:** il fumo materno è stato confermato come una variabile con impatto negativo altamente significativo sul peso alla nascita.
- **Predittori Positivi:** la durata della gestazione è stata validata come il principale driver positivo per il peso neonatale.
- **Validità Scientifica:** il modello finale è stato validato statisticamente, garantendo che le conclusioni non siano frutto del caso ma di relazioni robuste nei dati.

## Risultati Interattivi
Il report completo, con tutto il codice R e i grafici diagnostici interattivi, è consultabile qui:
**[Link al report su RPubs](https://rpubs.com/DaveDea/previsione_peso_neonatale](https://rpubs.com/DaveDea/lm_weight_birth_v2)**
