# idqapp.github.io

Home page principale di **IDQ** — sviluppatore indipendente di app Android (Riccione, Italia).

Questo repository è il *sito utente* di GitHub Pages: viene pubblicato sulla radice del dominio.
I siti dei singoli progetti restano nei loro repository e compaiono sotto il dominio come
sottocartelle (`/biker`, `/navigator`, `/monitor`, `/calendar`, `/converter`).

## File

- `index.html` — home page (sezioni: hero, progetti, chi sono, contatti)
- `404.html` — pagina di errore personalizzata
- `robots.txt`, `sitemap.xml` — SEO
- `site.webmanifest` — nome, colori e icone del sito
- `assets/` — marchio, favicon, immagine per i social (`og.png`) e icone dei progetti
- `CNAME` — dominio personalizzato (gestito da GitHub Pages)
- `.nojekyll` — disattiva Jekyll: i file vengono serviti così come sono

## Modifiche

Il sito è una pagina sola, senza build: si modifica `index.html` e si fa push su `main`.
La pubblicazione richiede circa un minuto.

Se cambia il dominio, vanno aggiornati: `CNAME`, i tag `canonical`/`og:url`/`og:image`
in `index.html`, `robots.txt` e `sitemap.xml`.

Contatto: info.idq.26@gmail.com
