# Eliza
<br>

**ELIZA** è un agente di conversazione, o *"chatbot"*, realizzato per la prima volta nel 1966 da *Joseph Weizenbaum*.
Aveva lo scopo di emulare uno psicologo. Da allora sono state realizzate diverse implementazioni, più o meno simili
a quelle originali. Ad esempio Emacs è in possesso di un programma di tipo **ELIZA** al suo interno.
La **CIA** ha anche sperimentato un'interrogazione informatica degli ufficiali che utilizzano una versione molto simile,
ma piuttosto combattiva del programma.
<br>

La mia implementazione si basa sul programma originale scritto da *Joe Strout*.
L'ho aggiornato in maniera significativa per utilizzare una forma più moderna per la sinstassi di Python,
ma i modelli di testo nelle strutture di dati riflessivi vengono copiati in modo verbale.
<br>

Noterete che la maggior parte del codice sorgente è composta da un dizionario chiamato reflections e un elenco di stringhe
chiamate *psicobabble*. **ELIZA** è fondamentalmente uno script con semplici istruzioni condizionali. Non c'è molto di più di questo.
