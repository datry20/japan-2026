# japan-2026

Due pagine statiche, nessuna dipendenza e nessun build.

- **`index.html`** — itinerario del viaggio in Giappone, maggio 2026.
- **`spese.html`** — app personale per le spese quotidiane in euro.

## Spese

Gestione spese mensili: aggiunta rapida, categorie con icona/colore/tetto,
budget mensile, grafico giornaliero e ripartizione per categoria, spese
ricorrenti automatiche, filtri e ricerca, export CSV.

I dati stanno **solo nel `localStorage` del browser**: nessun server, nessun
account, niente lascia il dispositivo. Di conseguenza si perdono se cancelli i
dati di navigazione o cambi dispositivo — usa *Dati → Esporta backup JSON* con
una certa regolarità, e *Importa* per rimetterli su un altro dispositivo.

È una PWA: da telefono, «Aggiungi a schermata Home» la installa e la rende
utilizzabile offline (`sw.js` + `manifest.webmanifest`).
