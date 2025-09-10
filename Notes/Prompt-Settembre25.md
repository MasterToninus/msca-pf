---
modified: 2025-09-08T23:32:45.887Z
title: null
---

Aiutami a riformulare in modo organico sotto forma di un paragrafo in inglese, adottando uno stile adatto ad una pubblicazione in Matematica pura, le seguenti informazioni frammentarie riguardanti un mio progetto di ricerca. Rifererisciti quando serve alle fonti della bibliografia che ti fornisco. Estrai informazioni tecniche rilevanti dalla bibliografia, dalle fonti dentro la bibliografia, e da internet. Il Livello deve essere specifico e tecnico. Fornisci un codice latex con le formule usando $ e $$. Di seguito indico tra parentesi quadre ulteriori direttive per te.

## Bibliografia:
* Bleeker https://books.google.it/books/about/Gauge_Theory_and_Variational_Principles.html?id=SFLCAgAAQBAJ&redir_esc=y
* Hamilton https://link.springer.com/book/10.1007/978-3-319-68439-0
* Meinrenken https://www.math.utoronto.ca/mein/teaching/MAT1341_LieGroupoids/Groupoids.pdf
* unpublished https://www.math.uni-potsdam.de/~paycha/paycha/Unpublished_notes_May_2022.pdf
* baezwise https://arxiv.org/abs/1204.4339
* wikipedia https://en.wikipedia.org/wiki/Frame_fields_in_general_relativity
* teleparallel https://ncatlab.org/nlab/show/teleparallel+gravity
* mckenzie https://www.cambridge.org/core/books/general-theory-of-lie-groupoids-and-lie-algebroids/DA70C6FAF52F88FB471F62DD68049608
* costaforgerpegas https://www.sciencedirect.com/science/article/pii/S0393044018301566?via%3Dihub 

## 1	Quality and pertinence of the project’s research and innovation objectives (and the extent to which they are ambitious, and go beyond the state of the art) #@QUA-LIT-QL@#

[introduzione al titolo al progetto]


1) Modello standard: particelle fisiche e mediatori dell’interazione (matematicamente fibrati e connessioni), classificazione tramite rappresentazioni di gruppi.
modello geometrico dello standard model basato su fibrati principali P con gruppo di struttura G, il  gauge group (inteso come “internal symmetry group”, il vero “gauge group” è Aut(P) = mappe da M al gruppo G) e fibrati vettoriali E associati  (Hamilton + Bleeker + consigli Fabrizio(?))
Classificazione delle particelle (di materia) tramite le rappresentazioni del gruppo di gauge G sulle fibre del fibrato associato E.
(Se c’è spazio    
Classificazione dei mediatori di forze (gauge bosons) come connessioni principali sul fibrato principale P (matematicamente 1-forme a valori nell’algebra di Lie di G)
PROBLEMA APERTO: è tutto su Minkowski, cosa si può fare su uno spazio tempo curvo?
2) Passaggio ai gruppoidi: simmetrie interne vs globali tramite gruppoidi
Fin qui è tutto su Minkowski, su spazitempo curvi si apre il problema che i gruppi di simmetria non sono sufficienti a formalizzare simmetrie locali, si passa ai gruppoidi (noi ci basiamo su Costa-Forger-Pegas, ricostruire chi è il precursore dello studio dei gruppoidi di simmetria). Forse OLVER? https://www-users.cse.umn.edu/~olver/mf_/sgwq.pdf	https://www.mdpi.com/2073-8994/13/10/1905
https://www.cambridge.org/it/universitypress/subjects/mathematics/algebra/general-theory-lie-groupoids-and-lie-algebroids?format=PB#contents
weinstein
Noi in GR abbiamo il problema degli osservatori, come minimo è una carta locale. Noi abbracciamo l’idea che sia anche centrato in quanto l’osservatore esiste in un punto (evento) dello spazio-tempo.
Problema: come confronto carte che sono centrate in punti diversi? Solitamente in geo diff si confrontano carte locali che mantengono l’origine. Su Minkowski siamo facilitati perché la carta centrata su ogni osservatore in realtà può avere un dominio esteso a tutto lo spaziotempo. Sul curvo due osservatori possono confrontare il valore dell’osservazione solo in eventi che giacciono nell’intersezione dei domini. Quando le due origini giacciono nell’intersezione dei domini, possiamo affrontare il problema dei cambi di carte, lo facciamo con il linguaggio dei jet (metodologia nuova). O meglio il problema della traslazione della carta:
Tecnicamente cosa facciamo? La traslazione dell’osservatore (visto come carta centrata) è formalizzata dal Pair Groupoid. Ma noi vogliamo di più, vogliamo confrontare i tangenti, ciò che consideriamo è il frame groupoid del tangente di M, GL(TM). Per rispettare la metrica bisogna considerare “l’orthogonal frame” (nel linguaggio di Forger), O(TM,g). Key fact: GL(TM) = J^1 Pair(M) (fonti: Meinrenken ex 1.12). Lo spirito è quello di generalizzare Poincaré su Minkowski ad un certo gruppoide su spazio tempo curvo. L’idea era in qualche modo già presente nell’articolo di Forger.
Infine bisogna parlare di covarianza. In RR è invarianza per il gruppo di Poincaré, in GR è invarianza per tutti i diffeomorfismi. noi ci mettiamo in un caso intermedio in cui il background è fisso (non siamo “in accoppiamento”). Forger parla già di Noether in questo contesto. (e di moment map)
PROBLEMI APERTI: Poincarè groupoid -> Spin extension
3) Gravitazione?
Essendo una forza dovrebbe essere trattata come un campo di gauge, ovvero modellata tramite una connessione su un fibrato principale.
Il primo passo è stato l’introduzione della tetrad (attribuita a Palatini o forse precedente? check wikipedia)
Ma la gravitazione non può essere codificata come gauge (la variabile dinamica è la tetrad). Baez ha tentato di codificare la gravitazione come connessione su un 2-fibrato (higher structures) ottenendo una descrizione della “teleparallel gravity”. Il problema è che stiamo promuovendo Poincaré ad un gruppo di simmetria interna.
Noi proponiamo di vedere Poincarè come gruppoide in modo da preservare lo statuto non locale della parte di traslazioni, (le lasciamo come esterne e non le promuoviamo ad interne come fa Baez)
PROBLEMA APERTO: continuando l’analogia vogliamo codificare il gravitone come connessioni a valori nei gruppoidi ( work in progress di Alessandra citare unpublished)
4) Osservabili multilocali
Fin qui abbiamo parlato molto di background. Vogliamo trattare anche i sistemi campo … in particolare la struttura algebrica degli osservabili.
menzionare qualcosa dell’approccio multisimplettico e della strana algebra L infinito di Rogers
Svolta fondamentale: lavoro di Alessandra sugli osservabili multilocali
PROBLEMA APERTO: claim del progetto ANR.  homotopy comomentum map associate all’azione di gruppoidi
obbiettivi “Describe how your project goes beyond the state-of-the-art,”
Elaborare un modello geometrico completo della teoria dei campi su spazio tempo curvo basato su simmetrie in termini di azioni di gruppoidi (in particolare le simmetrie di spazio tempo sono date dal gruppoide di Poincaré)
Nel modello di sopra: la gravitazione vista come tetrad verrebbe letta come connessione sull’algebroide di Lie del gruppoide di Poincaré
Nel modello sopra: per modellizzare i campi di materia (fermioni) è necessario elaborare una spin extension del Poincarè groupoid (mimando l’estensione del gruppo di Lorentz al gruppo Spin come ricoprimento universale)
5) “The extent to which the proposed work is ambitious.”
Dare risposta a problemi aperti in fisica teorica da oltre 50 anni.
Si basa su pubblicazioni e svolte molto recenti (vedi articoli di Forger e preprint di Alessandra. volendo anche Baez+Weiss e articoli multisimplettici per la parte in cui vengono usati)
L’elevata interdisciplinarietà del progetto accostata all’elevato grado di specializzazione richiesto nella comprensione sia del lato fisico (modello standard non è più “nuovo” ma è sempre molto sofisticato) che dal lato matematico (visto il grande utilizzo di higher structure che facciamo- gruppoidi, algebroidi, algebre a meno di omotopia)
6) “Are the objectives realistically achievable?”
Elaborazione già in corso da alcuni anni. noi proponiamo un contributo naturale ma non triviale
Le idee alla base di questo progetto sono frutto di una discussione congiunta e gruppi di lavoro attivi già da circa un anno e mezzo in the framework of Lyon-Djon-Metz phys math network.
I proponenti di questo progetto sono stati tra i principali organizzatori di questi gruppi di lavoro (giusto per dire che dovremmo essere le persone giuste a perseguire questo progetto di ricerca)
Il progetto si inquadra perfettamente nel gruppo di lavoro della host istitution (come spieghiamo meglio nella sottosezione sottostante)
L’approccio gruppoidale alle simmetrie rientra in un vasto progetto elaborato negli ultimi due anni dal gruppo di Lione  che vuole descrivere in maniera covariante tutti gli osservabili in teoria di campo, problema aperto da oltre 50 anni.




1.2 	Soundness of the proposed methodology (including interdisciplinary approaches, consideration of the gender dimension and other diversity aspects if relevant for the research project, and the quality of open science practices) 



Overall methodology: Describe and explain the overall methodology, including the concepts, models and assumptions that underpin your work. Explain how this will enable you to deliver your project’s objectives. Refer to any important challenges you may have identified in the chosen methodology and how you intend to overcome them.
implementiamo degli strumenti nuovi (intendo gruppoidi di simmetria, connessioni su gruppoidi e algebroidi, mappe momento associate a simmetrie gruppoidali) in ambiti consolidati ma comunque di frontiera (Modello standard e oltre, campi gravitazionali, relatività generale)
proponiamo un assunzione nuova, quella di sostituire la centralità del gruppo di Poincaré all’interno del modello standard con un nuovo gruppoide di Poincaré allo scopo di spingere l’applicabilità del modello standard anche nel contesto di background curvi.
important challenges: nuovo modello sofisticato sia dal punto di vista degli strumenti matematici (Gruppoidi, algebroidi e  cosiddette “higher structures") che dal punto di vista delle applicazioni al modello fisico (sia per quanto riguarda il gravitone che i problemi nell’elettrodebole relativi al campo di higgs)

Integration of methods and disciplines to pursue the objectives: Explain how expertise and methods from different disciplines will be brought together and integrated in pursuit of your objectives. 




Structure in six subsectionsas follows. Structure the fist two with two \paragraphs: state of the arts, open problems
1) Modello standard: particelle fisiche e mediatori dell’interazione (matematicamente fibrati e connessioni), classificazione tramite rappresentazioni di gruppi.
modello geometrico dello standard model basato su fibrati principali P con gruppo di struttura G, il  gauge group (inteso come “internal symmetry group”, il vero “gauge group” è Aut(P) = mappe da M al gruppo G) e fibrati vettoriali E associati  (Hamilton + Bleeker + consigli Fabrizio(?))
Classificazione delle particelle (di materia) tramite le rappresentazioni del gruppo di gauge G sulle fibre del fibrato associato E.
(Se c’è spazio    
Classificazione dei mediatori di forze (gauge bosons) come connessioni principali sul fibrato principale P (matematicamente 1-forme a valori nell’algebra di Lie di G)
PROBLEMA APERTO: è tutto su Minkowski, cosa si può fare su uno spazio tempo curvo?
2) Passaggio ai gruppoidi: simmetrie interne vs globali tramite gruppoidi
Fin qui è tutto su Minkowski, su spazitempo curvi si apre il problema che i gruppi di simmetria non sono sufficienti a formalizzare simmetrie locali, si passa ai gruppoidi (noi ci basiamo su Costa-Forger-Pegas, ricostruire chi è il precursore dello studio dei gruppoidi di simmetria). Forse OLVER? https://www-users.cse.umn.edu/~olver/mf_/sgwq.pdf	https://www.mdpi.com/2073-8994/13/10/1905
https://www.cambridge.org/it/universitypress/subjects/mathematics/algebra/general-theory-lie-groupoids-and-lie-algebroids?format=PB#contents
weinstein
Noi in GR abbiamo il problema degli osservatori, come minimo è una carta locale. Noi abbracciamo l’idea che sia anche centrato in quanto l’osservatore esiste in un punto (evento) dello spazio-tempo.
Problema: come confronto carte che sono centrate in punti diversi? Solitamente in geo diff si confrontano carte locali che mantengono l’origine. Su Minkowski siamo facilitati perché la carta centrata su ogni osservatore in realtà può avere un dominio esteso a tutto lo spaziotempo. Sul curvo due osservatori possono confrontare il valore dell’osservazione solo in eventi che giacciono nell’intersezione dei domini. Quando le due origini giacciono nell’intersezione dei domini, possiamo affrontare il problema dei cambi di carte, lo facciamo con il linguaggio dei jet (metodologia nuova). O meglio il problema della traslazione della carta:
Tecnicamente cosa facciamo? La traslazione dell’osservatore (visto come carta centrata) è formalizzata dal Pair Groupoid. Ma noi vogliamo di più, vogliamo confrontare i tangenti, ciò che consideriamo è il frame groupoid del tangente di M, GL(TM). Per rispettare la metrica bisogna considerare “l’orthogonal frame” (nel linguaggio di Forger), O(TM,g). Key fact: GL(TM) = J^1 Pair(M) (fonti: Meinrenken ex 1.12). Lo spirito è quello di generalizzare Poincaré su Minkowski ad un certo gruppoide su spazio tempo curvo. L’idea era in qualche modo già presente nell’articolo di Forger.
Infine bisogna parlare di covarianza. In RR è invarianza per il gruppo di Poincaré, in GR è invarianza per tutti i diffeomorfismi. noi ci mettiamo in un caso intermedio in cui il background è fisso (non siamo “in accoppiamento”). Forger parla già di Noether in questo contesto. (e di moment map)
PROBLEMI APERTI: Poincarè groupoid -> Spin extension
3) Gravitazione?
Essendo una forza dovrebbe essere trattata come un campo di gauge, ovvero modellata tramite una connessione su un fibrato principale.
Il primo passo è stato l’introduzione della tetrad (attribuita a Palatini o forse precedente? check wikipedia)
Ma la gravitazione non può essere codificata come gauge (la variabile dinamica è la tetrad). Baez ha tentato di codificare la gravitazione come connessione su un 2-fibrato (higher structures) ottenendo una descrizione della “teleparallel gravity”. Il problema è che stiamo promuovendo Poincaré ad un gruppo di simmetria interna.
Noi proponiamo di vedere Poincarè come gruppoide in modo da preservare lo statuto non locale della parte di traslazioni, (le lasciamo come esterne e non le promuoviamo ad interne come fa Baez)
PROBLEMA APERTO: continuando l’analogia vogliamo codificare il gravitone come connessioni a valori nei gruppoidi ( work in progress di Alessandra citare unpublished)
4) Osservabili multilocali
Fin qui abbiamo parlato molto di background. Vogliamo trattare anche i sistemi campo … in particolare la struttura algebrica degli osservabili.
menzionare qualcosa dell’approccio multisimplettico e della strana algebra L infinito di Rogers
Svolta fondamentale: lavoro di Alessandra sugli osservabili multilocali
PROBLEMA APERTO: claim del progetto ANR.  homotopy comomentum map associate all’azione di gruppoidi
obbiettivi “Describe how your project goes beyond the state-of-the-art,”
Elaborare un modello geometrico completo della teoria dei campi su spazio tempo curvo basato su simmetrie in termini di azioni di gruppoidi (in particolare le simmetrie di spazio tempo sono date dal gruppoide di Poincaré)
Nel modello di sopra: la gravitazione vista come tetrad verrebbe letta come connessione sull’algebroide di Lie del gruppoide di Poincaré
Nel modello sopra: per modellizzare i campi di materia (fermioni) è necessario elaborare una spin extension del Poincarè groupoid (mimando l’estensione del gruppo di Lorentz al gruppo Spin come ricoprimento universale)
5) “The extent to which the proposed work is ambitious.”
Dare risposta a problemi aperti in fisica teorica da oltre 50 anni.
Si basa su pubblicazioni e svolte molto recenti (vedi articoli di Forger e preprint di Alessandra. volendo anche Baez+Weiss e articoli multisimplettici per la parte in cui vengono usati)
L’elevata interdisciplinarietà del progetto accostata all’elevato grado di specializzazione richiesto nella comprensione sia del lato fisico (modello standard non è più “nuovo” ma è sempre molto sofisticato) che dal lato matematico (visto il grande utilizzo di higher structure che facciamo- gruppoidi, algebroidi, algebre a meno di omotopia)
6) “Are the objectives realistically achievable?”
Elaborazione già in corso da alcuni anni. noi proponiamo un contributo naturale ma non triviale
Le idee alla base di questo progetto sono frutto di una discussione congiunta e gruppi di lavoro attivi già da circa un anno e mezzo in the framework of Lyon-Djon-Metz phys math network.
I proponenti di questo progetto sono stati tra i principali organizzatori di questi gruppi di lavoro (giusto per dire che dovremmo essere le persone giuste a perseguire questo progetto di ricerca)
Il progetto si inquadra perfettamente nel gruppo di lavoro della host istitution (come spieghiamo meglio nella sottosezione sottostante)
L’approccio gruppoidale alle simmetrie rientra in un vasto progetto elaborato negli ultimi due anni dal gruppo di Lione  che vuole descrivere in maniera covariante tutti gli osservabili in teoria di campo, problema aperto da oltre 50 anni.