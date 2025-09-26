
<h1>Setup Web App React</h1>
 <b>repo:</b> webapp-react 

 <hr>
 
<b>Esercizio</b><br>

<b>MILESTONE 0</b> <br>
- Ragionare e preparare uno schemino per impostare la struttura del lavoro in maniera da sfruttare la riutailizzabilità dei componenti React e le loro props.<br><br>

<b>MILESTONE 1</b><br>
- Mettiamo su un nuovo progetto React aiutandoci con Vite,<br>
- Ripuliamo come sempre l’app da file e codice di esempio non necessari,<br>
- Installiamo il necessario: React Router, Axios e Bootstrap (se volete utilizzarlo)<br><br>

<b>MILESTONE 2</b><br>
- Creiamo un layout di base per la nostra applicazione ed impostiamo le rotte per le diverse pagine.<br>
- Creiamo 2 pagine: (1) La home, in cui mostreremo la lista dei film, (2) La pagina di dettaglio di un singolo film<br><br>

<b>MILESTONE 3</b><br>
- Configuriamo l’app di backend (repo webapp-express) a ricevere chiamate dalla nostra applicazione React, installando e impostando il middleware CORS,
Proviamo quindi ad effettuare una chiamata Ajax dalla home del progetto React, per ottenere la lista dei libri.<br><br>

<b>Bonus</b><br>
- Curare l’aspetto estetico della vostra applicazione,<br>
- Realizzare un modulo css da importare in una componente<br>

<hr>

<h2>Setup Web App React II</h2>

<b>MILESTONE 4</b><br>
- Continuate a lavorare sulla repo di react e se serve in quella di express per fare in modo che nella pagina di dettaglio ci sia una chiamata ajax che recupera il dettaglio del film comprese le sue recensioni.<br><br>

<b>Bonus</b><br>
- Curare l’aspetto estetico della vostra applicazione,<br>
- Realizzare le stelle con font-awesome per la media dei voti,<br>
- Realizzare i pulsanti per andare avanti ed indietro tra i film,<br>
- Realizzare la pagina NotFound<br>

<hr>

 <h2>Setup Web App React III</h2>

 Miglioriamo l’esperienza dell’utente inserendo:<br>
 
 <b>MILESTONE 1 (BACKEND)</b><br>
- Predisponiamo un’API per salvare nel database una nuova recensione legata ad un film,<br>
- Testiamola su postman e verifichiamo che nel DB venga effettivamente inserita una nuova recensione<br><br>

<b>MILESTONE 2 (FRONTEND)</b><br>
- Creiamo un componente che contenga il form per le recensioni,<br>
- Inseriamo questo componente nella pagina di dettaglio del film,<br>
- All’invio del form, la nuova recensione viene salvata sul database e visualizzata nella pagina, in fondo alle altre<br><br>

<hr>

<h2>Setup Web App React IV</h2>

<b>Esercizio</b><br>
- Concludiamo migliorando l’esperienza sulla nostra SPA, inserendo un loader.<br>
- Creiamo un componente loader,<br>
- Questo componente deve poter apparire su qualunque pagina della nostra app.,<br>
- Creiamo e sfruttiamo un Context per dare la possibilità ad ogni componente di attivare o disattivare il loader sulla propria pagina,<br><br>

<b>BONUS:</b><br>
- Personalizziamo l’aspetto della nostra app col CSS
