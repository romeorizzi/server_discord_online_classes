# Note del progetto 

## Link utili

- Pagina ufficiale di discord: https://discord.com/new
- docs: https://discord.com/developers/docs/intro
- api_reference: https://discord.com/api
- link_server_discord: https://discord.gg/v9bkMMd
	- questo è il server principale dal quale poi il modello va ad attigere per crearsi. 
- webhook: https://support.discord.com/hc/it/articles/228383668
	- permettono di raccogliere informazioni da siti o app esterne in tempo reale
<hr/>

## Creazione server usando un template:
- modello: https://discord.new/ameWUFBTH38F
	- basta cliccare e inserire un nome per usare questo modello come template per il server discord.
<hr/>

## Notes
- registrazione video tramite obs. si può fare di meglio? magari con bot?
- streaming dipendente da connessione sia per emitente che per ricevente.

## info varie


Il server che ho creato e sotto la voce Modello è un template e si puo duplicare avendo un link e assegnando un nome, poi in automatico discord provvede a creare una copia per l'utente. questa copia sembra non modificabile esternamente e quindi non si può modificare il server principale e aspettarsi che le copie ottengano la stessa modifica. se però dopo l'update si riutilizza il link si va a scaricare la nuova versione del server. quindi creare tale server, duplicarlo per avere la versione base e poi modificare dinamicamente quello che verrà poi usato effettivamente.
Da quello che ho potuto vedere dei template che mi ha dato il più interessante sembra quello con il bot, solo perchè appunto c'è il bot. tutte le stanze e i canali presenti si possono tranquillamente generare magari partendo da uno studio su quante e quali stanze effettivamente servono: breaking room etc. Esiste anche un modo per assegnare i ruoli in modo automatico attraverso un bot. Potrebbe essere un miglioramento interessante anche se non obbligatorio tanto che si potrebbe considerare il ruolo @everyone come studente e semplicemente creare un ruolo @docente che sarebbe l'admin.

Se posso consigliare per un server scolastico adotterei una linea di tipo minimale e senza troppi arricchimenti bottistici. sicuramente alcuni possono essere utili ma non li reputo indispensabili tanto che per spostare gli studenti tra le varie stanze si possono tranquillamente trascinare da una stanza vocale ad un'altra.

1) la ricerca dei materiali al momento la sto acquisendo per poi scrivere un report con una visione un pò più ampia.

2) Il canle telegram se ha lavorato bene consiglierei di tenerlo. non penso sia saggio creare un bot che metta in copia telegram con discord in quanto arriverebbero le notizie due volte e per coloro che hanno sia discord che telegram arriverebbe doppia notifica(anche se si possono gestire) eventualmente in futuro la cosa si può cambiare, questo è il bello di discord customizabile e dinamico in ogni momento.

3) da discord non è possibile registrare, è stato richiesto gia un anno fa ma non è ancora stato implementato e non sembra essere nei piani futuri e quindi serve per forza un programma esterno. obs va bene anche se penso possa andare bene un qualunque programma base che registri audio e video. obs non è un pregramma ready to use in quanto necessità di un setup anche se minimo.

4) le breaking room possono essere gestite in due modi: o manualemnte dove si fa drag and drop degli studenti(no randomicità) oppure attraverso il bot moover(si randomicità e "riga di comando", in realtà si scrive un messaggi in un canale testuale e si usa quel canale come terminale per il bot)

5) Per il calendario delle lezioni si potrebbe integrare se non ho capito male attraverso i webhook. devo indagare ancora su questo aspetto.

Concludendo penso che il miglior prossimo step sia continuare a guardare server discord già fatto per capire chi prima di noi ha usato questo strumento per cercare di capire cosa sia superfluo e cosa indispensabile, fare qualche prova con i webhook che potrebbero essere molto interessanti forse anche per bypassare la questione del terminale?(ipotesi non confermata)
