# Quaderno di Kendra

App web personale per obiettivi (con punti), spese, acqua bevuta e riepilogo del mese.

- I file del sito vengono pubblicati con GitHub Pages dalla cartella principale.
- I dati sono salvati su Supabase nella tabella `quaderno_kendra`, protetti da login e da regole di accesso: ognuno vede solo i propri dati.
- In `config.js` ci sono solo l'indirizzo del progetto e la chiave pubblica: nessuna password.
- I promemoria arrivano dalla funzione "promemoria" del progetto Supabase, con frasi gentili.
