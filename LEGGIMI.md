# I miei esami — istruzioni

Sito con il menu dei 7 esami del primo anno di Lettere (UniMC), a più livelli.

## Cosa c'è nella cartella

- `index.html` — la pagina del sito (non serve modificarla)
- `menu.json` — il contenuto del menu: esami, sottomenu, link e file
- `file/` — la cartella dove mettere i tuoi file (PDF, Word, PowerPoint, Excel…)
- `.nojekyll` — file tecnico per GitHub Pages, lascialo così

## Pubblicare il sito su GitHub (una volta sola)

1. Su github.com crea un nuovo repository, ad esempio `esami`, **pubblico**.
2. Nella pagina del repository premi **Add file → Upload files** e trascina **tutto il contenuto** di questa cartella (anche la cartella `file`). Premi **Commit changes**.
3. Vai su **Settings → Pages**. In *Branch* scegli `main` e la cartella `/ (root)`, poi **Save**.
4. Dopo un minuto o due il sito è online all'indirizzo `https://TUONOME.github.io/esami/`.

## Modificare il menu

1. Apri il sito e premi **✎ Modifica**.
2. In ogni livello puoi aggiungere un **sottomenu** o un **collegamento o file**, rinominare (✎), spostare (↑ ↓) ed eliminare (🗑).
3. Le modifiche restano subito nel tuo browser. Per pubblicarle per tutti:
   premi **Scarica menu.json**, poi su GitHub **Add file → Upload files**, trascina il file scaricato e premi **Commit changes**. Sostituisce quello vecchio.

## Aggiungere un tuo file (PDF, Word, PowerPoint, Excel)

1. Su GitHub entra nella cartella `file` e premi **Add file → Upload files**, trascina il file e conferma.
2. Sul sito, in modalità Modifica, aggiungi un **collegamento** e come indirizzo scrivi `file/` seguito dal nome esatto, ad esempio `file/appunti lezione 3.docx`.

Consiglio: usa nomi di file senza accenti né apostrofi.

## Nota

Se apri `index.html` con un doppio clic dal computer, il sito mostra solo i 7 esami vuoti: il menu completo si legge solo quando il sito è pubblicato.
