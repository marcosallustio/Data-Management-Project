Nota per l'utilizzo di youtube scrape and api.ipynb:
	L'API di Google permette di fare solo 10000 richieset API GET al giorno, avendo nel codice fatto 3 richieste contemporaneamente
    (per avere diverse statistiche), l'API key inserita si esaurirà dopo circa 3000 video.
    Sarà quindi necessario (se il dataset contiene più valori) creare un nuovo progetto sulla dashboard developer fornita da Google 
    e generare un'altra API key, facendo ripartire il codice dal punto in cui si è fermato