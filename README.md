# FORM 88 v2.1

PWA personale, mobile-first e offline per seguire il piano alimentare FORM 88.

## Novità della v2

- gamification sana basata sull'aderenza ai comportamenti, mai sul dimagrimento o sulla restrizione;
- punteggio giornaliero, totale, streak, livelli e Reward Wallet con soglia configurabile;
- Meal Builder con aggiunta, rimozione, sostituzione e modifica delle grammature;
- ricalcolo automatico di calorie, proteine, carboidrati e grassi con confronto rispetto al pasto base;
- ricette coerenti con il piano, incluse salse zero/low-cal e condimenti;
- indicazioni Turni integrate nella sezione Pasti;
- tracking di peso e passi con dati salvati solo nel browser;
- export e import del backup locale in formato JSON;
- installazione PWA e uso offline.

## Aggiornamento v2.1

- catalogo di alimenti con valori indicativi per 100 g, campi correggibili e anteprima dei macro in base ai grammi;
- pasto al lavoro come riferimento: pasta integrale o riso in bianco, fonte proteica variabile sotto i 100 g; macro non conteggiati senza porzioni note;
- lista della spesa dei pasti scelti con ingredienti sommati, ripetizione per 1–7 giorni e spunte locali; pasto al lavoro escluso;
- peso e passi registrabili separatamente durante la giornata, con punti distinti;
- tema chiaro/scuro persistente sul dispositivo e rimozione del riquadro Regola dalla Home.

## Privacy

Pasti personalizzati, spesa, tracking, punti e riscatti sono salvati nel `localStorage` del dispositivo. Non vengono inviati a server o al repository. L'utente può esportare volontariamente un backup JSON. La preferenza del tema è locale e separata dal backup.

## Pubblicazione

Ogni push sul branch `main` avvia il workflow GitHub Pages incluso nel repository.
