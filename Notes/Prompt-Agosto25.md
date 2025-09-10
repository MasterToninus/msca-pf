Aiutami a riformulare in modo organico sotto forma di un paragrafo in inglese, adottando uno stile adatto ad una pubblicazione in Matematica pura, le seguenti informazioni frammentarie riguardanti un mio progetto di ricerca. Rifererisciti quando serve alle fonti della bibliografia che ti fornisco. Estrai informazioni tecniche rilevanti dalla bibliografia, dalle fonti dentro la bibliografia, e da internet. Il Livello deve essere specifico e tecnico. Fornisci un codice latex con le formule usando $ e $$. Di seguito indico tra parentesi quadre ulteriori direttive per te.

## Bibliografia:
* CostaA: https://arxiv.org/abs/1508.04632
* CostaB: https://arxiv.org/abs/1806.01329
* Paycha: https://www.math.uni-potsdam.de/~paycha/paycha/Unpublished_notes_May_2022.pdf
* nlabA: https://ncatlab.org/nlab/show/gauge+group
* wiki: https://en.wikipedia.org/wiki/Lie_groupoid


## Idee sparse
* in CostaA si parla di isometry groupoid (controllo su che tipo di varietà specifico). L'idea del progetto è di promuovere la centralità di questo oggetto ad diventare l'analogo su spazio tempo curvo di ciò che è il gruppo di Poincarè. Per questo intendiamo chiamarlo "Gruppoide di Poincarè"
* Un ingrediente importante è fornito dall'esempio 3 di CostaA, in cui si stabilisce che il Frame Groupoid è isomorfo al Jet groupoid del Pair Groupoid [Fornisci frasi esplicative di cosa sia il pair groupoid e il frame groupoid]
* Il Poincarè groupoid di M è per definizione il sottogruppoide o gauge groupoid del frame [Fornisci definizione e spiegazione di cosa sia un gauge groupoid] ma in generale non è un gruppoide di Jet.
* quando guardo le bisezioni [spiegazione di cosa sono le bisezioni nel contesto dei gruopoids] ottengo una mappa dal gruppoide al gruppo delle bisezioni [vedi CostaA pag 12, eq 42 e eq 43]
* in Generale è possibile costruire una sequenza di mappe dal gruppoide al gruppo delle bisezioni al gruppo dei diffeomorfismo della varietà. La seconda mappa in generale non è un inclusione ma SE il gruppoide è regular allora è una mappa regolare [spiega cosa significa] e inoltre quando il gruppoide è di Gauge l'anchor è transitiva e la seconda mappa è una inclusione e anche sommersione [controlla che questa frase abbia senso]. Il Gruppoide di poincarè è di quest'ultimo tipo.
* Gruppoide di Frame è anche un gruppoide di Jet [capire cosa significa]. Guardando le bisezioni del Poincarè uno si può chiedere se queste sono holonomous rispetto al Jet (ref CostaA sez 3.2, esempio 4). Punto chiave è che in uno spaziotempo non è mai holonomous. per dare senso a questa affermazione bisogna parlare di Jet di un gruppoide.
* La sezione 4 di CostaA studia le azioni di un gruppoide su un fibrato vettoriale. Prova che c'è un invarianza della forma canonica [cita in modo dettagliato il teorema 1].
* A pagina 32 di CostaA è da capire il teorema 2 dove parte da un gruppoide G, considera J^1G = Frame considera il sottogruppoide full [capire definizione di sottogruppoide full] come Gauge Groupoid
* La sezione 5 di CostA propone un estensione della momentum map nel caso di azioni di gruppoide [menziona dettagliatamente il contento della sezione] e propone un teorema di Noether
* La sezione 6 di CostaA contiene una descrizione dettagliata del campo scalare su SpazioTempo curvo, eq.158 fornisce l'analogo dello energy momentum tensor associato all'invarianza per il gruppoide di Poincarè

## Long term goals (big plan)
* formalizzare i campi di Gauge come connessioni su un gruppoide non solo infinitesimale

## Short term goals
* Comprensione degli articoli CostaA e CostaB [menziona gli open problems menzionati in quegli articoli]
* Estendere e precisare il principio di covarianza su spazio tempo curvo in termini del gruppoide di poincarè
* Nel caso piatto i Fermioni escono da un rilevamento universale del gruppo di poincarè al gruppo spin. E' possibile mimare questa costruzione anche nel caso del gruppoide di poincarè (ovvero ottenere uno Spin Groupoid)? quello che si ottiene è una buona nozione di spinore su spazio tempo curvo?
* è possibile estendere la nozione di momentum map di CostaA all'ambito multisimplettico? ovvero, posso dare una Homotopy comomentum map nel caso di azioni hamiltoniane di grouppoidi?