# Studio Legale Avv. Giovanni Tedesco - Sito Web

Questo repository contiene il codice sorgente del sito web dello Studio Legale Avv. Giovanni Tedesco.
Si tratta di un sito web statico, progettato con un approccio mobile-first e sviluppato utilizzando esclusivamente HTML5, CSS3 e JavaScript puro (nessun framework esterno).

## Tecnologie utilizzate
*   **HTML5:** Struttura semantica delle pagine.
*   **CSS3:** Stile, layout responsive (CSS Grid e Flexbox) e design.
*   **JavaScript (ES6):** Gestione del menu mobile (hamburger) e interazioni fluide.

## Struttura del progetto
*   `index.html`: Homepage
*   `studio.html`: Presentazione dello studio e metodo di lavoro
*   `aree-attivita.html`, `urgenze-penali.html`, `appello-cassazione.html`, `esecuzione-detenuti.html`: Pagine specifiche per le aree di competenza
*   `contatti.html`: Pagina dei contatti e mappa interattiva (il form di contatto è stato rimosso per compatibilità con piattaforme completamente statiche come Cloudflare Pages)
*   `privacy.html`, `cookie.html`: Informative legali 
*   `style.css`: Foglio di stile globale
*   `main.js`: Script per la logica dell'interfaccia utente (menu mobile, smooth scroll)
*   `sitemap.xml`, `robots.txt`: File di configurazione per la SEO e l'indicizzazione sui motori di ricerca
*   `img/`: Cartella contenente le risorse grafiche (`hero-legale.png`, `entrata-studio.jpg`)

## Come avviare il progetto in locale
Poiché si tratta di un sito puramente statico, non è necessario alcun server di sviluppo, ambiente Node.js o processo di build.
È sufficiente fare doppio clic sul file `index.html` per aprirlo direttamente nel proprio browser web preferito e testarlo.

## Pubblicazione
Il progetto è ottimizzato, leggero e pronto per essere ospitato su piattaforme di hosting statico e CDN ad alte prestazioni come **Cloudflare Pages**, **GitHub Pages** o **Netlify**.
Trattandosi di file statici, non è richiesto alcun backend o database.
