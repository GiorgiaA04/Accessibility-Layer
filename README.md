# Accessibility-Layer
Prototipo di un livello di personalizzazione dell'accessibilità cognitiva per siti web.

# Descrizione
Accessibility Layer è un prototipo sviluppato nell'ambito di un progetto di tesi presso l'Alma Mater Studiorum, Università di Bologna.
Il progetto esplora la possibilità di integrare in un sito web, principalmente di argomento didattico, un insieme di strumenti per personalizzare la presentazione dei contenuti e facilitare l'orientamento e la consultazione delle informazioni.

Il componente è stato progettato per essere integrato in pagine HTML esistenti, senza richiedere la ricostruzione dell'intero sito. 

# Funzionalità
Il prototipo comprende:
- Personalizzazione del testo: scelta del carattere tipografico (Serif, Sans Serif e Atkinson Hyperlegible) e regolazione progressiva della dimensione.
- Spaziatura: regolazione dell'interlinea e della spaziatura tra lettere e parole.
- Contrasto: modalità origiale, contrasto elevato e contrasto invertito.
- Ripristino: possibilità di riportare le personalizzazioni ai valori iniziali.
- Glossario: visualizzazione dei termini e delle relative definizioni con possibilità di evidenziarli nel testo.
- Riassunti: visualizzazione di contenuti sintetici associati alle pagine o a specifiche sezioni.
- Indice dei contenuti: generazione di collegamenti ai titoli presenti nella pagina.
- Memorizzazione delle preferenze: salvataggio delle impostazioni nel browser tramite localStorage.

# Requisiti
- Una pagina HTML con un contenitore principale identificabile tramite un selettore CSS
- Un browser moderno con supporto a JavaScript e localStorage.
- Un ambiente servito tramite HTTP o HTTPS per il caricamento dei file JSON.
Non sono richieste librerie JavaScript esterne.

# Integrazione
Il componente è pensato per essere integrato in un sito HTML esistente.
1. Copiare la cartella accessibility-layer nella directory principale del sito
2. Collegare lo script JavaScript e lo stylesheet CSS dopo la disponibilità del documento.
3. Verificare la presenza del contenitore principale dei contenuti.
4. Configurare i percorsi dei file JSON in base alla struttura del sito ospitante.

Il contenitore principale deve corrispondere al selettore configurato in accessibilityConfig, inizialmente impostato su #main-content.

I percorsi dei dati sono configurabili attraverso le proprietà glossaryPath e summariesPath.

I file JSON devono rispettare la struttura dei dati prevista dal codice: il glossario utilizza una raccolta terms, mentre i riassunti utilizzano una raccolta summaries.

# Personalizzazione dei contenuti
I contenuti del glossario e dei riassunti sono definiti nei rispettivi file JSON e possono essere adattati alle pagine e agli argomenti del sito ospitante.

I riassunti presenti nella demo hanno valore esemplificativo e possono essere sostituiti o personalizzati dallo sviluppatore del sito.

# Demo
Il componente è stato integrato e sperimentato all'interno di un sito dimostrativo dedicato alla letteratura italiana. 

https://giorgiaa04.github.io/Percorsi-nella-letteratura-italiana/

# Limiti del prototipo
Accessibility Layer è un prototipo sperimentale e non costituisce una certificazione di accessibilità del sito in cui viene integrato.

L'efficacia della personalizzazione dipende anche dalla strutura HTML, dagli stili e dai contenuti del sito ospitante. L'integrazione richiede pertanto verifiche specifiche sul contesto di utilizzo.

# Disclaimer
Il prototipo ha finalità di ricerca e sperimentazione nell'ambito dell'accessibilità cognitiva e della personalizzaione dell'esperienza di consultazione dei contenuti web. 
  
