# Slot Map Viewer (PWA)

Viewer sola-lettura per mappa slot machine. **Nessun dato incluso**: carichi il tuo file `.sqlite` in-app (resta locale, salvato in IndexedDB del browser).

Live: https://persiano8787.github.io/slot-map-viewer/

## Aggiornare l'app
1. Modifica `index.html` (copia da `SLOT_MAP/app/viewer.html`).
2. Bump `CACHE = 'slotmap-vN'` in `sw.js`.
3. `git commit && git push`. Il telefono aggiorna alla 2ª apertura con rete.
