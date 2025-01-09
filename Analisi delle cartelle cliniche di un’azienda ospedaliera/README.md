# Analisi delle cartelle cliniche di un’azienda ospedaliera

## Contesto Aziendale
Un'azienda ospedaliera necessita di un sistema efficiente per gestire le cartelle cliniche dei pazienti. Questo sistema deve essere in grado di:
- Memorizzare i dettagli di ogni paziente e dei loro ricoveri.
- Consentire analisi sui tempi di ricovero per migliorare la gestione ospedaliera.

MongoDB è stato scelto come database per la sua capacità di gestire dati strutturati e semi-strutturati, nonché per la sua flessibilità nel modellare dati complessi come i ricoveri dei pazienti.

## Obiettivi del Progetto
1. Creare un database MongoDB per memorizzare le cartelle cliniche.
2. Popolare il database con dati di prova.
3. Analizzare i tempi medi di ricovero.

## Requisiti dei Dati

- **Paziente**:
  - Nome (Stringa)
  - Ricoveri (Array di Documenti):
    - Data (ISODate)
    - Diagnosi (Stringa)
    - Anamnesi (Stringa)
    - Prognosi (Stringa)
    - Data di Dimissione (ISODate)

## Fasi del Progetto

### 1. Creazione del Database e delle Collezioni
Lo studente deve creare uno script per:
- Creare un database chiamato `cartelle_cliniche`.
- Creare una collezione chiamata `pazienti` che memorizzi i dati sopra descritti.

### 2. Inserimento dei Dati di Prova
Inserire nel database almeno:
- 5 pazienti, ognuno con almeno 2 ricoveri.

### 3. Analisi dei Tempi di Ricovero
Scrivere uno script per:
- Calcolare il tempo medio (in giorni) che intercorre tra la data di ricovero e la data di dimissione per tutti i pazienti.
- Mostrare i risultati in un formato leggibile.


## Conclusioni
Questo progetto permette di gestire efficacemente le cartelle cliniche dei pazienti e offre insight utili per ottimizzare la gestione ospedaliera. I dati analizzati possono supportare decisioni strategiche e migliorare la qualità dei servizi offerti.
