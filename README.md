# Sito Michela Vecchi Psicologa — bozza redesign

Sito statico (solo HTML/CSS, nessuna build necessaria), con struttura ispirata
al layout di esterfantonipsicologa.it ma con identità grafica propria
("Un nuovo sguardo" — motivo dell'anello/lente, palette blu-petrolio + terracotta
su fondo carta).

## Come vederlo online con GitHub Pages

1. Crea un nuovo repository su GitHub (es. `sito-michela-preview`).
2. Carica tutto il contenuto di questa cartella nella root del repository
   (index.html, chi-sono.html, ecc. devono stare nella root, non in una sottocartella).
3. Vai su **Settings → Pages** del repository.
4. In "Build and deployment" scegli **Deploy from a branch**, branch `main`,
   cartella `/root`.
5. Dopo circa un minuto il sito sarà visibile su
   `https://<tuo-utente>.github.io/<nome-repo>/`

## Cosa manca ancora (segnaposto da sostituire)

Cerca nel codice il tag `<span class="placeholder-flag">` per trovare tutti i punti
con testo segnaposto da sostituire con contenuti reali di Michela:

- Bio completa nella pagina "Chi sono"
- Elenco servizi reali nella pagina "Di cosa mi occupo"
- Testo dettagliato dell'approccio clinico
- Indirizzo studio, telefono, mappa
- Eventuali testimonianze / recensioni, se vuole includerle

Le pagine `chi-sono.html`, `di-cosa-mi-occupo.html`, `il-mio-approccio.html` e
`contatti.html` sono per ora solo stub di navigazione: la struttura visiva è pronta
(stessi componenti della home — intestazioni, sezioni split, sezione scura contatti),
ma vanno riempite pagina per pagina con i contenuti veri.

## File

- `index.html` — homepage completa
- `chi-sono.html`, `di-cosa-mi-occupo.html`, `il-mio-approccio.html`, `contatti.html` — stub
- `css/styles.css` — tutto lo stile del sito
