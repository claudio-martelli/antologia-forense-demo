# Testi

I file contenenti materiale protetto da Copyright sono vuoti, rimane la struttura e qualche cenno a fini esemplificativi. Per informazioni circa la creazione + esempi tratti dal file annotato: [`../docs/presentazione-progetto.pdf`]

- **`dieci-piccoli-indiani.txt`** — testo integrale del romanzo (traduzione italiana), senza annotazioni. Utile come riferimento "puro" o per generare versioni annotate di altre opere.
- **`dieci-piccoli-indiani-annotato.txt`** — stesso testo, con i tag di regia inseriti per l'LLM (`[FASE 0...]`, `[SCENA n]`, `[FOCUS: ...]`, `[RICOMPENSA...]`). È il file da allegare al modello insieme al prompt e al cronogramma.
- **`gioco-di-ruolo-riferimento.txt`** — testo enciclopedico generale sui giochi di ruolo, usato come riferimento di base per impostare il tono e il comportamento del Game Master.

## Tag di annotazione usati nel testo annotato

| Tag | Significato |
|---|---|
| `[FASE 0: PARTE NARRATIVO-INTRODUTTIVA]` | Blocco di introduzione, da sintetizzare prima dell'inizio del gioco |
| `[SCENA n]` ... `[/SCENA n]` | Delimita il contenuto di una scena giocabile, corrispondente a una voce del cronogramma |
| `[FOCUS: ...]` | Istruzione di regia su come narrare un dettaglio specifico (es. non rivelare troppo presto un indizio) |
| `[RICOMPENSA INTUIZIONE DEGNA DI NOTA / BRILLANTE]` ... `[/...]` | Punto in cui, se i giocatori anticipano una deduzione, va assegnata una carta bonus |

Per la logica completa dietro questi tag, vedi [`../prompt/cronogramma.md`](../prompt/cronogramma.md).
