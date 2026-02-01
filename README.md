# progetto-ai2
# Analisi Termografica per la Stima della Temperatura Corporea

Questo progetto utilizza modelli di regressione lineare per stimare la temperatura orale partendo da dati termografici facciali.

## Gruppo di lavoro
* Francesco Borgogni
* Andrea De Simone
* Roberto Serafini

## Dataset
Viene utilizzato il dataset **Infrared Thermography Temperature** (UCI ID: 925).

## Librerie utilizzate
* `pandas` e `numpy` per la manipolazione dati.
* `seaborn` e `matplotlib` per l'analisi esplorativa (EDA).
* `scikit-learn` per il preprocessing e il modello ElasticNet.

### ⚠️ Avvertenze importanti
**Tempo di esecuzione del Pairplot**: Nella sezione di Analisi Esplorativa (EDA), viene generato un pairplot. A causa dell'elevato numero di feature e della densità dei dati, la generazione di questo grafico può richiedere diversi minuti (**circa 2-3 minuti**).

## Riproducibilità
* Le librerie utilizzate e il dataset vengono importate automaticamente.
* Il random state dello split è 42.
