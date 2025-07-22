Questa cartella contiene il codice e il dataset utilizzati per un progetto di authorship attribution previsto dal corso di Linguistica computazionale II dell'Università di Pisa (a.a. 2024/2025).

Il task è stato svolto a partire dai testi delle scrittrici italiane ottocentesche Neera, Marchesa Colombi e Matilde Serao.

La cartella contiene:

- La cartella "Codice" con i notebook del progetto, in ordine di creazione, che comprendono:
    - Creazione del dataset (da 0 a 3)
    - Risoluzione del task con SVM e informazioni linguistiche non lessicali estratte dal tool ProfilingUD (4)
    - Risoluzione del task con SVM e n-grammi estratti dai file connlu annotati dal tool Profiling UD (5)
    - Risoluzione del task con SVM e word-embeddings per l'italiano a 128 dimensioni (6). Nel file 6.1, il codice per la conversione dei word-embeddings da .sqlite a .txt
    - Risoluzione del task con Bert base italian uncased (7)
      
- Il file profilingud.csv, con le features estratte dal tool di annotazione e nel file dizionario_features.json il dizionario delle stesse
  
- La cartella "Testi Progetto", con i testi originali del progetto scaricati dal Progetto Gutemberg e le versioni normalizzate degli stessi
  
- La cartella "Dataset", con i file creati estraendo dai testi solo i paragrafi di lunghezza compresa tra 50 e 100 token, uno per file
  
- Il file dizionario_paragrafi.json, ovvero il dizionario dei paragrafi estratti
  
- La cartella "Dataset connlu",con i file annotati dal tool ProfilingUD
  
- La relazione che illustra ogni fase di svolgimento del progetto

N.B: i file sono stati riordinati per rendere più comoda la consultazione delle cartelle. Per l'esecuzione dei notebook, si raccomanda di aggiornare i path dove necessario.

N.B2: per limitare le dimensioni della cartella, non sono stati caricati i file dei word-embeddings e i checkpoint prodotti da BERT.
