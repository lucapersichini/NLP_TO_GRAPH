--------------------------------------------------
ENG
--------------------------------------------------

Title: Building a 3D Knowledge Graph from Text

Description:

This project implements a system for extracting information from text and building a three-dimensional knowledge graph. The system utilizes the following technologies:

SpaCy: For natural language processing of the text, such as identifying subjects, objects, and relations.
FastText: To obtain word embeddings, which are used to calculate semantic similarity between words and for concept clustering.
NetworkX: For creating and manipulating the knowledge graph.
Scikit-learn: For the KMeans clustering algorithm, used to group words into concepts.
Plotly: For 3D visualization of the knowledge graph.
How it Works:

The input text is processed by SpaCy to identify relationships between words.
FastText embeddings are used to calculate similarity between words and for concept clustering.
A knowledge graph is built using NetworkX, where nodes represent words and edges represent relationships between them.
Concepts are identified by grouping similar words using KMeans.
The knowledge graph is visualized in 3D using Plotly.
Usage:

Make sure you have the necessary libraries installed: gensim, spacy, numpy, torch, networkx, scikit-learn, fastText, plotly.
Download the Italian language model for SpaCy: python -m spacy download it_core_news_md.
Download FastText embeddings for the Italian language.
Run the main code to process the text and build the knowledge graph.
Visualize the knowledge graph using the visualize_graph_3d function.
Example:

A complex example text is provided to demonstrate the capabilities of the system. The resulting knowledge graph can be explored and analyzed to understand the relationships between the concepts extracted from the text.

Notes:

The code was developed and tested in Google Colab.
You can save and load the state of the knowledge graph for later use.
Contact:

For questions or suggestions, contact lucapersichini

















---------------------------------------
ITA
---------------------------------------
Titolo: Costruzione di un Grafo di Conoscenza 3D da Testo

Descrizione:

Questo progetto implementa un sistema per estrarre informazioni da un testo e costruire un grafo di conoscenza tridimensionale. Il sistema utilizza le seguenti tecnologie:

SpaCy: Per l'analisi linguistica del testo, come l'identificazione di soggetti, oggetti e relazioni.
FastText: Per ottenere embeddings di parole, che vengono utilizzati per calcolare la similarità semantica tra le parole e per il clustering di concetti.
NetworkX: Per la creazione e la manipolazione del grafo di conoscenza.
Scikit-learn: Per l'algoritmo di clustering KMeans, utilizzato per raggruppare le parole in concetti.
Plotly: Per la visualizzazione 3D del grafo di conoscenza.
Funzionamento:

Il testo di input viene elaborato da SpaCy per identificare le relazioni tra le parole.
Gli embeddings di FastText vengono utilizzati per calcolare la similarità tra le parole e per il clustering di concetti.
Un grafo di conoscenza viene costruito utilizzando NetworkX, dove i nodi rappresentano le parole e gli archi le relazioni tra di esse.
I concetti vengono identificati raggruppando le parole simili tramite KMeans.
Il grafo di conoscenza viene visualizzato in 3D utilizzando Plotly.
Utilizzo:

Assicurarsi di avere installato le librerie necessarie: gensim, spacy, numpy, torch, networkx, scikit-learn, fastText, plotly.
Scaricare il modello di lingua italiana per SpaCy: python -m spacy download it_core_news_md.
Scaricare gli embeddings di FastText per la lingua italiana.
Eseguire il codice principale per elaborare il testo e costruire il grafo di conoscenza.
Visualizzare il grafo di conoscenza utilizzando la funzione visualize_graph_3d.

Esempio:

Viene fornito un esempio di testo complesso per dimostrare le capacità del sistema. Il grafo di conoscenza risultante può essere esplorato e analizzato per comprendere le relazioni tra i concetti estratti dal testo.

Note:

Il codice è stato sviluppato e testato in Google Colab.
È possibile salvare e caricare lo stato del grafo di conoscenza per un utilizzo successivo.
Contatti:

Per domande o suggerimenti, contattare lucapersichini.
