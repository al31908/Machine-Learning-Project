# Machine-Learning-Project
## Descrizione del Progetto
Questo progetto mira a prevedere il rapporto like/visualizzazioni e commenti/visualizzazioni dei post video (reels) di un profilo Instagram scelto. Le fasi principali del progetto comprendono:

**Scraping dei dati**: Raccolta di informazioni sui post video tramite l'API di Instaloader.

**Analisi descrittiva**: Esplorazione e visualizzazione dei dati per comprendere meglio il comportamento del pubblico.

**Machine Learning**: Sviluppo di modelli predittivi per stimare il rapporto like/view e commenti/view.


## Struttura del Progetto



**1. Scraping dei dati**

Il codice nella cartella scraping/ estrae i dati dei reels da Instagram. I dati includono:

**Media ID**: Identificatore unico del video.

**Data di pubblicazione**: Data in cui il video è stato pubblicato.

**Durata del video**: Durata del video in secondi.

**Visualizzazioni**: Numero di visualizzazioni.

**Likes**: Numero di "mi piace".

**Commenti**: Numero di commenti



**2. Analisi Descrittiva**

La cartella analisi_descrittiva/ contiene codice per l'analisi esplorativa dei dati. Alcune delle analisi effettuate includono:

Creazione di nuove feature: Rapporto likes/visualizzazioni e commenti/visualizzazioni.

Distribuzione delle visualizzazioni e interazioni nel tempo.

Durata media dei video e classificazione in base ai quantili.

Relazioni tra variabili (likes, commenti, visualizzazioni).


**Funzioni principali:**

visualizzazioni_data(): Grafico dell'andamento delle visualizzazioni nel tempo.

likes_data(): Analisi dei "mi piace" nel tempo.

durata_video(): Classificazione dei video in base alla durata.

rel_varibili(): Esplora le relazioni tra le variabili principali (likes, commenti, visualizzazioni).



**3. Machine Learning**

Nella cartella machine_learning/, sono implementati diversi algoritmi di regressione per prevedere:

Rapporto likes/visualizzazioni.

Rapporto commenti/visualizzazioni.

Gli algoritmi utilizzati includono:

Decision Tree Regressor.

Random Forest Regressor.

AdaBoost Regressor.



**Fasi:**

Caricamento e trasformazione dei dati: I dati vengono trasformati per il training dei modelli.

Creazione dei set di training e test.

Creazione e valutazione del modello.

Gradient Boosting Regressor.

Support Vector Regressor (SVR).



## Valutazione dei Modelli

La valutazione dei modelli viene effettuata utilizzando la cross-validation con metriche come:

R² (coefficiente di determinazione).

MAE (Mean Absolute Error).

MSE (Mean Squared Error).

RMSE (Root Mean Squared Error).
