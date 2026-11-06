# Globalizzazione — Quinta LES

Sito didattico per la quinta del liceo delle scienze umane, opzione economico-sociale. Contiene 10 capitoli di sintesi, 30 termini di glossario, ripasso per l’orale e 12 domande con correzione commentata.

## Aprire il sito sul computer

Aprire `index.html` con un doppio clic. Non occorre installare programmi. Il sito funziona anche senza connessione; soltanto i collegamenti alle fonti esterne richiedono Internet. Il pulsante “Stampa / salva PDF” apre la stampa del browser, dove è possibile scegliere “Salva come PDF”.

## Pubblicare su GitHub Pages dal browser

1. Creare il proprio account su https://github.com e confermare l’indirizzo email.
2. Dopo l’accesso, usare il pulsante **+**, quindi **New repository**.
3. Come nome del repository scrivere **globalizzazione-les**. Scegliere **Public**, selezionare **Add a README file** se disponibile e premere **Create repository**. Il repository è lo spazio in cui saranno conservati i file del sito.
4. Nel repository scegliere **Add file → Upload files**. Se si dispone solo dello ZIP, estrarlo prima con **Estrai tutto**. Aprire la cartella estratta e caricare il suo CONTENUTO, non lo ZIP e non una cartella contenitore. `index.html`, `stile.css`, `app.js`, `favicon.svg` e `README.md` devono essere visibili direttamente nel repository. Caricare anche `.nojekyll` se visibile: è un file vuoto intenzionale; il sito statico funziona anche se il caricamento dal browser lo omette.
5. Premere **Commit changes** e confermare il salvataggio sul ramo principale (`main`). “Commit” significa registrare i file caricati.
6. Aprire **Settings → Pages**. Sotto **Build and deployment**, impostare **Source: Deploy from a branch**. Scegliere **Branch: main** e cartella **/(root)**. Premere **Save**.
7. Attendere che GitHub completi la pubblicazione. Riaprire **Settings → Pages** e usare **Visit site** o il collegamento indicato nella pagina. L’indirizzo sarà `https://NOMEUTENTE.github.io/globalizzazione-les/`, sostituendo NOMEUTENTE con il nome effettivo dell’account. Non è un indirizzo già attivo.
8. Aprire l’indirizzo anche sul telefono e provare indice, ricerca del glossario e quiz. Quello è il collegamento da inviare agli studenti.

Se non compare la scelta `main`, verificare di avere salvato i file. Se compare un errore 404, verificare che `index.html` sia nella pagina principale del repository e che Pages usi `main` e `/(root)`. Per eventuali errori di pubblicazione consultare la scheda **Actions**. I nomi dei pulsanti possono cambiare in base alla lingua dell’interfaccia.

Guida ufficiale verificata il 6 novembre 2026: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Contenuti e fonti

La sezione “Fonti e metodo” documenta tutti i 17 file originali, raggruppati in 9 nuclei, e i riferimenti usati nei singoli capitoli. La sintesi distingue dati storici, interpretazioni e precisazioni metodologiche. I testi integrali originali e le loro immagini non sono inclusi nella cartella pubblicabile.

## Scelte tecniche

HTML, CSS e JavaScript senza librerie esterne, compilazione o database. I percorsi sono relativi, compatibili con un sito GitHub Pages di progetto. Nessun font remoto, pubblicità, tracciamento o invio dei risultati del quiz. Le risposte vengono gestite nella pagina e si azzerano al suo ricaricamento.

Per aggiornare il sito, sostituire nel repository i file modificati tramite **Add file → Upload files** e salvare con **Commit changes**. GitHub Pages aggiornerà il sito automaticamente. Conservare una copia locale dei file.
