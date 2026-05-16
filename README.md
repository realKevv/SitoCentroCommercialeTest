Progetto: Piattaforma Web - Centro Commerciale (Vendita Spazi)

Questo repository contiene il codice sorgente (HTML5 e CSS3 nativi) per la piattaforma web di un centro commerciale focalizzato sulla vendita e il noleggio di spazi commerciali, uffici e locali interni.

Offerta Tecnica e Scelte Progettuali

1. Obiettivo del Sito
L'obiettivo principale della piattaforma è attirare brand, commercianti e investitori interessati ad aprire un'attività all'interno del centro commerciale.

2. Architettura dell'Informazione (Pagine)
Il sito si compone di un minimo di due pagine web collegate tra loro:
`index.html` (Home Page): Presentazione generale, punti di forza del centro (attrazioni, eventi), panoramica dei locali commerciali disponibili con call-to-action e form di contatto finalizzato alla lead generation.
`locali.html` (Dettaglio Locali): Pagina di approfondimento dedicata alla visualizzazione dettagliata degli spazi immobiliari in vendita/affitto.

### 3. Design, Layout e Sistema di Colori (CSS Vanilla)
* **Layout Grid & Flexbox: Per garantire la massima pulizia visiva e il rispetto dei requisiti tecnici, la galleria dei locali e le sezioni informative utilizzano CSS Grid (es. `grid-template-columns: repeat(3, 1fr)`).
* **Tema Cromatico:** Il design segue una palette calda basata sul **giallino/oro** (come da mockup dell'immobile), bilanciata da toni scuri per i testi e i pulsanti principali per garantire un ottimo contrasto e accessibilità.

Variabili CSS utilizzate:
    :root {
    --colore-primario: #dcb34e;
    --colore-primario-light: #ebd083;
    --colore-scuro: #3e3e40;
    --colore-testo: #1a1a1a;
    --colore-sfondo: #f9f8f3;
    --sfondo-card: #ffffff;
    --gap-griglia: 30px;
}

---

Struttura delle Pagine (Dettaglio Componenti)

`index.html` (Home Page)
1.  **Navbar:** Barra di navigazione superiore contenente il logo del centro commerciale e i link rapidi alle sezioni interne.
2.  **Hero Section:** Sfondo principale con titolo principale (`<h1>`), breve testo descrittivo dell'opportunità di business e un pulsante d'azione "*Scopri di più*" (disabilitato temporaneamente o con link interno).
3.  **Section Info ("Dove ci troviamo", "Eventi", "Attrazioni"):** Sezione testuale descrittiva che introduce i punti di forza strategici del centro (presenza di cinema, parco giochi e aree di intrattenimento per attirare pubblico).
4.  **Sezione Locali Disponibili (Grid 3 Card):** Galleria fotografica disposta su griglia a 3 colonne che mostra i locali commerciali (ispirata al mockup fornito). Ogni card presenta un pulsante funzionante che reindirizza l'utente a `locali.html`.
5.  **Sezione Attrazioni (Grid 3 Card):** Presentazione visiva dei servizi ancora presenti (Cinema, Parco Giochi, Area Food).
6.  **Sezione Eventi (Grid 3 Card):** Prossimi eventi in programma nel centro commerciale per dimostrare il forte afflusso di clienti.
7.  **Lead Generation Form:** Un form di contatto per richiedere informazioni o preventivi sui locali commerciali.
8.  **Footer:** Chiusura della pagina con copyright, contatti e link utili.

---

**To-Do List** (Cose da fare per terminare il progetto)

### HTML & Struttura
- [x] Creare il file `index.html` e impostare lo scheletro con i tag semantici (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`).
- [x] Implementare la Navbar e la Hero Section con i relativi testi.
- [x] Configurare la sezione descrittiva delle Attrazioni ed Eventi del centro commerciale.
- [x] Inserire i blocchi delle Card (3 per i Locali, 3 per le Attrazioni).
- [x] Creare il form di contatto a fine pagina per la raccolta dati dei potenziali clienti.
- [x] Creare il secondo file `locali.html` strutturato per l'approfondimento immobiliare.


### CSS & Stile
- [x] Creare il file `style.css` e locali.css inizializzare le variabili CSS nel `:root` per il tema giallino e i font.
- [x] Configurare il layout della Grid obbligatoria per le sezioni a 3 card, assicurando la responsività.
- [x] Stilizzare i pulsanti (in particolare quello scuro con scritta bianca "*Scopri di più*").
- [x] Associare i link corretti ai pulsanti delle card dei locali per fare in modo che puntino a `locali.html`.


### Revisione e Consegna
- [ ] Commentare accuratamente ogni blocco di codice HTML e ogni regola CSS complessa (Requisito fondamentale del test).
- [x] Verificare la corretta visualizzazione del layout della griglia.
- [ ] Effettuare il push finale del codice sul repository Git condiviso con i partner del progetto.
