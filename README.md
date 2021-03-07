# calci8

L'obbiettivo dell'applicativo è permettere di comporre le squadre per il gioco del fantacalcio.
Il metodo di asseganzione dei giocatori alle squadra (e.g. asta a rilancio) è arbitrario e non deve essere gestito.

Tutti i dettagli dei giocatori sono disponibili a partire da un file csv
L'utilizzo dell'applicativo deve essere suddiviso in almeno tre fasi:
-settaggio dei criteri di formazione delle squadre
-assegnazione dei giocatori alle squadre
-composizione dei file di resoconto 

FASE 1 - settaggio 

Il primo passo è quello di decidere tutti i dettagli della composizione delle squadre, tra cui:
-numero di squadre iscritte
-numero di giocatori per squadra e numero di giocatori per ruolo
-crediti disponibili per l'acquisto dei giocatori
-metedo di selezione dei giocatori (a chiamata* o per estrazione randomica**)


FASE 2 - assegnazione giocatori

Una volta inziata l'asta si dà il via alla selezione dei giocatori in una delle due modalità (ricerca o random)
Deve essere possibile estrarre sia per ordine di ruoli (e.g. prima portieri poi difensori e così via...) sia tra tutti i disponibili senza seguire alcun ordine.
Una volta decisa la squadra che si è aggiudicata il giocatore deve essere possibile assegnarlo solo se ha ancora slot disponibili per il ruolo corrente e se ha crediti disponibili (Il costo dei giocatori è deciso dai giocatori per esempio attraverso un'asta)
Attenzione che i crediti non devono solo coprire il costo di quel giocatore ma anche dei rimanenti (almeno 1 credito per ogni slot ancora vuoto)

FASE 3 - resoconto

Una volta che tutti i giocatori hanno completato la propria squadra deve essere possibile scaricare e/o stampare un resoconto delle squadre con tutte le info del caso (giocatori, costi, crediti rimanenti,...)
Può essere una buona idea poter anche salvare online il resoconto studiando una semplice politica di accesso



* a chiamata prevede che la scelta del giocatore da assegnare sia fatta appunto chiamando a turno il giocatore desiderato
** per estrazione significa che il giocatore da assegnare è estratto a caso tra quelli disponibili
