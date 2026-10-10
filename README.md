# TeamWear Scanner

Scanner barcode/QR per articoli TeamWear, installabile come PWA su Android (e iOS/desktop).

- Legge EAN-13/8, UPC, Code128/39/93, Codabar, ITF, QR, Data Matrix, Aztec, PDF417 dalla fotocamera.
- Confronta ogni codice con un catalogo importato via CSV (esportato da Danea Easyfatt — nessuna API live disponibile, vedi sezione "Limiti" nell'app).
- Ad ogni scansione puoi impostare Ubicazione e Quantità e premere **Carica** per tenere la riga in memoria.
- **Termina** genera un file `.xlsx` con la data odierna, nella stessa struttura del file "Import Danea Inventario" (Ubicazione, Cod., Descrizione, Cod. a barre, Taglia/Colore, Udm, Giacenza Easyfatt, Giacenza effettiva), pronto per il reimport manuale in Easyfatt.
- Elaborazione 100% locale nel browser: nessun dato lasciato questo repo o inviato a server esterni.

## Uso

Apri l'URL di GitHub Pages di questo repo da Chrome su Android, poi menu ⋮ → **Installa app**.

La fotocamera funziona solo su HTTPS (o localhost) — non aprire `index.html` come file locale su mobile, non funzionerà come app installabile.
