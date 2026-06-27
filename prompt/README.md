# Prompt e Cronogramma

Questi due file costituiscono il "cervello" della Voce Narrante (il Game Master LLM). Vanno sempre allegati **insieme**, oltre al testo annotato e al manuale.

- **[`prompt-master.txt`](prompt-master.txt)** — il prompt di sistema: istruisce il modello su ruolo (Voce Narrante senza memoria), tono (solenne, stile Christie, senza meta-narrazione), comportamento generale e sui file da leggere prima di rispondere.
- **[`cronogramma.md`](cronogramma.md)** — la "regia" scena per scena: per ogni scena definisce l'introduzione narrativa, i turni interattivi, il limite di carte utilizzabili, l'esplorazione statica disponibile e le condizioni per assegnare le ricompense (intuizioni "degne di nota" o "brillanti").

## Perché esiste il cronogramma

Come spiegato in [`../docs/meccaniche-di-gioco.md`](../docs/meccaniche-di-gioco.md) (sezione 4.2), il solo testo annotato non bastava a mantenere l'LLM coerente tra una sessione e l'altra: si perdeva tra le informazioni narrative e non distingueva bene le parti "da raccontare" da quelle "interattive". Il cronogramma risolve il problema imponendo una struttura a cascata (scena → introduzione narrativa → turni) che il Master deve seguire pedissequamente.

## Come usarli

All'avvio di una nuova sessione, allega all'LLM, in quest'ordine:

1. `prompt-master.txt`
2. `cronogramma.md`
3. `../testi/dieci-piccoli-indiani-annotato.txt`
4. `../testi/dieci-piccoli-indiani.txt`
5. `../testi/gioco-di-ruolo-riferimento.txt`
6. `../docs/manuale-di-gioco.md`

Poi avvia la conversazione (anche con un semplice messaggio di saluto): il Master risponderà con la formula di benvenuto fissa e la Fase 0 introduttiva.
Nel caso in cui l'LLM non dovesse avviare correttamente la Fase 0 come da manuale basta ricaricare il primo prompt inviato per reindirizzare la narrazione. Probabile errore di runtime nel processo di reasoning
