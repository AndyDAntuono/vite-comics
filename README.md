/* CONSEGNA */

Esercizio di oggi: Vite DC Comics
nome repo: vite-comics
Descrizione:
Create un nuovo progetto utilizzando Vite e Vue 3 e definite i componenti necessari per strutturare il layout come da
screenshot allegato.
Quando la struttura a macroblocchi è pronta, popolate le voci di menu dinamicamente usando i data del componente.
Per oggi diamo priorità alla struttura: quando è tutto bello solido, passiamo al Sass!
Numero minimo di push: 12
Se volete potete utilizzare bootstrap installandolo con npm. Per le icone di fontawesome potete installare il pacchetto oppure usare la cdn.
Bonus:
Creare un componente aggiuntivo per gestire la fascia azzurra con le icone.

- So che per il momento ho replicato l'esercizio di venerdì ma l'ho fatto per allenarmi con la nuova sintassi e i nuovi passaggi della creazione dei files;
- aggiungo/creo la cartella img all'interno della cartella assets (che a sua volta si trova nella cartella src) per aggiungere le immagini necessarie per progetto;
- installo bootstrap con il comando: npm install bootstrap;
- installo sass con il comando: npm add -D sass;
- all'interno della cartella src, creare la cartella styles e all'interno di quest'ultima creare il file generals.scss
- importo il file genrals nel fil app.vue scrivendo...
    <style lang="scss">
    @use './styles/generals.scss';
    </style>
- creo il file AppHeader.vue;
- nel file AppHeader.vue, sezione script, inserisco un array di oggetti rappresentante la barra di navigazione;
- nel file AppHeader.vue, sezione template creo una struttura rigida contenente il contenuto dell'header
- sempre nella sezione template applico un v-for per tutte le voci della barra di navigazione;
- nel file AppHeader, sezione style, creo delle classi peronalizzate per la barra di navigazione. In particolare imposto che la voce attiva del menu si colori di blu ed appaio un effetto sottolineato (ho usato un border bottom) del medesimo colore.