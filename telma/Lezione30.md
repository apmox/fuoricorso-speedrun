# Lezione 30
## Argomenti trattati
- Additive manufacturing
	- Passaggi del processo
	- Caratteristiche del processo
	- Storia del processo
	- Applicazioni del processo
	- Classificazione dei processi
		- Metalli
		- Polimeri
	- Processi con polimeri
		- Stereolitografia
		- Fused Deposition Modeling
		- Polyjet
		- Nanoscribe SLA
	- Analisi del tempo ciclo

## Esercizi
- Stereolitografia
- FDM

## Domande
- A cosa si riferisce il termine Additive Manufacturing? (Il processo per la produzione di oggetti tridimensionali strato per strato, in addizione, opposto ai metodi convenzionali di lavorazione per asportazione)
- In cosa consiste il processo di Additive Manufacturing e quali sono le sue fasi principali? (Preparazione disegno, conversione in mesh superficiale, conversione in linguaggio macchina, installazione macchina, costruzione pezzo, rimozione dal piatto, post-processing, applicazione)
- Dove e come viene stampato un componente nel processo di additive manufacturing? (Su di una piattaforma; in diversi orientamenti)
- Cosa comporta l'orientamento di un pezzo nel processo di additive manufacturing? (Diversa microstruttura)
- In cosa consiste il passaggio di impostazione della macchina nel processo di additive manufacturing? (Scelta parametri: velocità, tipo traiettoria, spessore del livello)
- Quali sono le principali criticità nell'additive? (Mancano riferimenti normativi per comparare il pezzo; proprietà meccaniche dipendenti fortemente dalla qualità del processo)
- Perché l'additive riduce la catena di processo per la realizzazione di un pezzo? (Complessità e personalizzazione del pezzo non aumentano complessità del processo)
- In cosa consiste l'ottimizzazione topologica? (Riduzione della massa di un componente realizzabile soltanto con additive manufacturing)
- Quali sono i limiti dell'additive manufacturing? (Dimensioni del pezzo, produzione in serie, scelta dei materiali, proprietà dei materiali (anisotropia, porosità))
- Cosa si intende per Rapid Prototyping?
- Cosa si intende per Rapid Casting?
- Cosa si intende per Rapid Tooling?
- Quale aspetto distingue le categorie dei processi di Additive Manufacturing? (Il materiale di stampa, metallo o polimero)
- In cosa consiste il processo di stereolitografia? (Vasca con polimero liquido, piattaforma, fascio di luce UV polimerizza sul piano di fuoco, piattaforma si muove; rimozione dalla piattaforma; eventuale ripolimerizzazione con luce UV)

- In cosa consiste il processo di Fused Deposition Modeling? (Filamento viene spinto attraverso pulegge (feeder) nel melter e poi nell'estrusore. Il getto sciolto di plastica solidifica nel piano di appoggio. L'estrusore si sposta in 3d)
- A cosa serve il materiale di supporto nel Fused Deposition Modeling? (Materiale di prestazioni meccaniche scadenti atto a riempire lo spazio necessario per fornire appoggio al materiale del pezzo)
- Che finitura superficiale hanno i componenti realizzati con Fused Deposition Modeling? (Scarsa, 0.1 mm, scalini visibili ad occhio nudo)

- In cosa consiste il processo di polyjet? (Getto polimerico indurente viene applicato a struttura di supporto)
- Quali finiture superficiali sono ottenibili con il polyjet?
- Perché nel polyjet non ho bisogno di postprocessing?

- Quali precisioni si riescono ad ottenere con processi innovativi di stereolitografia? (tolleranze sotto il micron)

- Da cosa dipende il tempo ciclo nei processi di additive manufacturing? (Dimensioni, numero di parti, tipo di processo, velocità di posizionamento lungo le 3 direzioni, ritardi)
- Come si stima il tempo per completare un livello di stampa nei processi di additive manufacturing? (Area del livello divisa per velocità di spot e diametro spot. All'area sommo il tempo di ricopertura.)
- Da quali fattori è composto il tempo di ricopertura? (Riposizionamento della testa di lavoro; riposizionamento della piattaforma; distesa materiale per nuovo strato; ritardi di riscaldamento o raffreddamento degli ugelli)
- Da cosa è dovuto il tempo di setup nel processo di additive manufacturing? (Tempo operatore per caricare il materiale; tempo riscaldamento della camera)
- Come si stima il tempo ciclo totale? (Tempo di setup Tsu, tempo per ogni layer)