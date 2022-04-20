# Makeblock 2. 
![makblock](https://user-images.githubusercontent.com/101712850/159687623-676cfbba-26b8-42e6-a253-81b026de61da.jpg)
 
 
### Che cos'è makeblok?
Makeblock 2 è un robot personalizzabile da assemblare da zero con i pezzi che vengono dati in dotazione,si habnno vari metodi di assemblamento e danno tutti una funzione diversa al robot.Uno si chiama Robotic Arm Tank che consiste in una specie di ruspa con un braccio meccanico fatto muovere attraverso un motore elettrico e puo sollevare oggietti di vario tipo ad esempio una pallina oppure una bottiglia puo inoltre muoversi su vari terreni grazie a dei cingoli fatti di gomma.
Poi si ha il beverage bot che ha un supporto sopra che si muove a diverse angolazioni e puo supportare una bottiglia d'acqua e versare l'acqua in un bicchiere.
Infine si ha il Camera Dolly che è un robot che attraverso un supporto che gira a 360° permette di e registrare video attraverso una video camera installata sopra.




![wall e ](https://user-images.githubusercontent.com/101712850/160784886-c796e22a-1f64-4551-8a94-6ac10a84b788.jpg)




## Costruzione 
per costrire arm tank nella scatola avevamo a disposizione attrezzi per montare il robot, l'assemblaggio è stato molto semplice perchè era presente il libretto da seguire passo dopo passo. Finito questo passaggio siamo passati alla parte robotica con la quale la ruspa si può muovere in tutte le direzioni, può muovere il braccio meccanico e può prendere gli oggetti come viene presentato nel video.

<iframe width="560" height="315" src="https://www.youtube.com/embed/LZ1nzw_RosA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Collegamento del robot mBot al software mBlock 

Per collegare mBot al PC e programmarlo puoi utilizzare il software proprietario mBlock, sia nella versione desktop che in quella online, con o senza registrazione.

Il collegamento del robot può avvenire attraverso tre tipi di connessione:
*cavo USB
*modulo Bluetooth
*modulo 2.4 G

Una volta avviato il programma, il primo passo che devi eseguire è far comparire nella scheda “Dispositivi” il blocco di Ultimate 2.0 e di conseguenza i blocchi di programmazione specifici. Per farlo clicca sulla scheda “Dispositivi” e poi sul pulsante “aggiungi” situato a sinistra della schermata fai doppio clic su “Ultimate 2.0” 
![mbot 2](https://user-images.githubusercontent.com/101712850/164213106-b26eb676-1201-4007-b4d9-92d88a823c03.png)





## Programmazione

Nella categoria “Azione” sono racchiuse tutte le istruzioni che gestiscono i motori. Avrai notato che  dovrai settare i valori di potenza, invece il controllo temporale non viene effettuato e il motore sarà sempre acceso fintantoché non verrà utilizzata l’istruzione di stop (l’ultima della lista). 

L’istruzione “vai avanti alla potenza 50%” svincola, invece, il movimento del robot dal tempo, permettendoti di scegliere soltanto la potenza e, dal menu a tendina, una delle quattro direzioni.

![macblock avanti](https://user-images.githubusercontent.com/101712850/161962883-c1e638f2-d35f-432b-ba4c-68ab8a0de64b.png)

Per gestire completamente lo spostamento di mBot puoi utilizzare invece questo script: ad ogni freccia direzionale è associato un comportamento, il movimento si ferma premendo la barra spaziatrice.

![mbot](https://user-images.githubusercontent.com/101712850/164207248-e44665e1-b7e9-4a48-975d-10a5d3ca40a0.png)





