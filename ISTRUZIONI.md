# Spiaggia App — Istruzioni pubblicazione

## File da caricare su GitHub

Rinomina `spiaggia_v3.html` → `index.html` prima di caricare.

Struttura cartella da caricare:
```
index.html        ← (era spiaggia_v3.html)
manifest.json
sw.js
icon-192.png      ← crea un'icona semplice (vedi sotto)
icon-512.png      ← crea un'icona semplice (vedi sotto)
```

---

## Come creare le icone (2 minuti)

1. Vai su https://favicon.io/favicon-generator/
2. Scrivi "⛱" come testo, sfondo #0e1117, testo bianco
3. Scarica → trovi icon-192.png e icon-512.png
4. Caricali insieme agli altri file

---

## Pubblicazione su GitHub Pages

1. Vai su github.com → "New repository"
2. Nome: `spiaggia-app` (o come vuoi)
3. Visibilità: **Public** (necessario per GitHub Pages gratis)
4. Clicca "Create repository"
5. Carica tutti i file (drag & drop nella pagina del repo)
6. Vai su **Settings → Pages**
7. Source: "Deploy from a branch" → branch: `main` → cartella: `/ (root)`
8. Clicca Save → aspetta 1-2 minuti
9. GitHub ti darà un URL tipo: `https://tuonome.github.io/spiaggia-app`

Quel link funziona da qualsiasi telefono, anche senza WiFi (dopo la prima apertura).

---

## Installare come app su iPhone (Safari)

1. Apri il link con **Safari** (non Chrome — su iPhone solo Safari supporta PWA)
2. Tocca il tasto **Condividi** (quadrato con freccia su)
3. Scorri e tocca **"Aggiungi a schermata Home"**
4. Dai un nome (es. "Spiaggia") → tocca **Aggiungi**
5. L'icona appare sulla schermata home — si apre come un'app a schermo intero

## Installare come app su Android (Chrome)

1. Apri il link con **Chrome**
2. Tocca i tre puntini in alto a destra
3. Tocca **"Aggiungi a schermata Home"** o **"Installa app"**
4. Conferma → l'icona appare sulla schermata home

---

## Note importanti

- Il **titolare** usa la tab "✏️ Modifica" per posizionare gli ombrelloni dal PC
  (drag per spostare, angolo in basso a destra per ridimensionare)
- Le posizioni si salvano nel browser — se cambi dispositivo, fai il layout una volta sola
  dal PC titolare e poi non toccare
- L'aggiornamento è automatico ogni 25 secondi — il puntino verde = connesso
- Il backend `.gs` rimane lo stesso della versione precedente (non serve riconfigurarlo)
