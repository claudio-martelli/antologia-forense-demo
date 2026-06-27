# Antologia Forense — Demo *Dieci Piccoli Indiani*

**Antologia Forense** è un gioco di ruolo educativo, cooperativo e card-driven, in cui i giocatori diventano **detective letterari**: il loro compito è esplorare il mondo narrativo di un'opera letteraria e aiutare una Voce Narrante — un modello linguistico (LLM) nel ruolo di Game Master — a ricostruire la storia che ha "dimenticato".

Questa repository contiene la **demo basata su *And Then There Were None* (Dieci Piccoli Indiani) di Agatha Christie, 1939**, sviluppata come progetto per un esame universitario incentrato sulla progettazione di giochi da tavolo educativi.

> Lo scopo del gioco non è vincere punti, ma **ricostruire fedelmente la trama**: chi sono i personaggi, cosa accade, in quale ordine, chi è il colpevole e come agisce — guidando la Voce Narrante a ritrovare la propria memoria capitolo dopo capitolo.

---

## 📁 Struttura della repository

```
antologia-forense-demo/
├── README.md                       → questo file
├── LICENSE                         → licenza del materiale originale (regole, manuale, prompt, codice)
├── NOTICE.md                       → nota sul copyright del testo di Agatha Christie e uso didattico
├── CREDITS.md                      → crediti e ruoli del team
│
├── docs/
│   ├── manuale-di-gioco.md         → manuale di gioco completo (regole, carte, modalità, schede personaggio)
│   ├── meccaniche-di-gioco.md      → presentazione delle meccaniche di gioco (relazione d'esame)
│   ├── concettualizzazione-prototipo.md → documento di ideazione e concettualizzazione (relazione d'esame)
│   ├── report-tecnico-v0.1.pdf     → report tecnico/funzionale/didattico completo del progetto
│   └── presentazione-progetto.pdf  → presentazione generale del progetto
│
├── prompt/
│   ├── prompt-master.txt           → prompt di sistema per configurare l'LLM come Game Master
│   └── cronogramma.md              → cronogramma scena-per-scena: la "regia" narrativa del Master
│
├── testi/
│   ├── dieci-piccoli-indiani.txt           → testo integrale del romanzo (traduzione italiana)
│   ├── dieci-piccoli-indiani-annotato.txt  → stesso testo, annotato con i tag di regia per l'LLM
│   └── gioco-di-ruolo-riferimento.txt      → testo di riferimento generale sui giochi di ruolo
│
├── schede-personaggio/
│   └── schede-personaggio.pdf      → schede dei 10 personaggi in formato infografico
│
├── carte/
│   └── carte-esempi.pdf            → esempi delle carte azione (Interroga, Esamina Oggetto, Suggerimento, Accusa)
│
├── board/
│   └── (tabellone di gioco — da aggiungere)
│
├── assets/
│   └── bozze-generazioni-nanobanana.pdf  → bozze del workflow di generazione immagini (sketch → Nanobanana → cardmaker)
│
└── partite-esempio/
    ├── README.md                          → indice e link alla partita originale
    ├── esempio-partita-01.md              → trascrizione leggibile della partita di esempio
    └── esempio-partita-01-raw.txt         → trascrizione grezza originale (con prompt completo)
```

---

## 🎲 Come funziona il gioco

Il gioco si basa su due livelli che interagiscono costantemente:

1. **Livello digitale** — un LLM configurato come *Voce Narrante* tramite il [prompt di sistema](prompt/prompt-master.txt) e il [cronogramma](prompt/cronogramma.md), che gestiscono scena per scena cosa il Master può narrare, rivelare o tenere nascosto.
2. **Livello fisico** — un mazzo di **carte azione** (`Interroga`, `Esamina Oggetto`, `Suggerimento`, `Accusa`), **schede personaggio** e un **tabellone**, che razionano le interazioni dei giocatori e ne rendono ogni scelta consapevole.

Le regole complete, le modalità di gioco (Normale, Esplorazione Libera, Personalizzata) e i codici per i facilitatori/insegnanti (`NOLIMITETURNI`, `IGNORACARTE`, ecc.) sono descritti nel [Manuale di Gioco](docs/manuale-di-gioco.md).

### Avviare una sessione con un LLM

Per giocare è necessario fornire all'LLM, prima dell'avvio, i seguenti documenti come contesto/allegati:

1. [`prompt/prompt-master.txt`](prompt/prompt-master.txt) — istruzioni di sistema
2. [`prompt/cronogramma.md`](prompt/cronogramma.md) — struttura scena per scena
3. [`docs/manuale-di-gioco.md`](docs/manuale-di-gioco.md) — regole e schede personaggio
4. [`testi/dieci-piccoli-indiani.txt`](testi/dieci-piccoli-indiani.txt) — testo integrale senza tag e pulito da formattazione
5. [`testi/dieci-piccoli-indiani-annotato.txt`](testi/dieci-piccoli-indiani-annotato.txt) — testo con i tag di regia
6. [`testi/gioco-di-ruolo-riferimento.txt`](testi/gioco-di-ruolo-riferimento.txt) — documento cardine sul ruolo di Master


Un esempio di sessione reale, generata con questa configurazione, è disponibile in [`partite-esempio/`](partite-esempio/).

---

## 🎓 Contesto e finalità

Questo progetto è stato realizzato per un esame universitario di progettazione di giochi da tavolo educativi. È pensato per studenti di scuola secondaria di secondo grado o universitari, in contesto scolastico o laboratoriale, con l'obiettivo di sviluppare:

- comprensione analitica di un testo narrativo complesso;
- ragionamento inferenziale e abduttivo;
- capacità di argomentare un'ipotesi con prove testuali;
- familiarità con le strutture narrative del genere giallo.

Per maggiori dettagli su obiettivi educativi, target e valutazione, vedi [`docs/concettualizzazione-prototipo.md`](docs/concettualizzazione-prototipo.md) e [`docs/meccaniche-di-gioco.md`](docs/meccaniche-di-gioco.md).

---

## ⚠️ Nota sul copyright

Questa repository NON include il testo integrale (in traduzione italiana) del romanzo *And Then There Were None* di Agatha Christie, anche se utilizzato **esclusivamente per finalità didattiche e di documentazione di un progetto d'esame**, non per distribuzione commerciale. Leggi la nota completa in [`NOTICE.md`](NOTICE.md) prima di qualsiasi riuso o pubblicazione del materiale.

---

## 👥 Crediti

Progetto realizzato da **Claudio Martelli**, **Arianna Berrafato** e **Daniele Rizzo**. Dettagli sui ruoli in [`CREDITS.md`](CREDITS.md).

## 📄 Licenza

Il materiale originale del progetto (manuale, meccaniche, prompt, cronogramma) è distribuito sotto licenza MIT come descritto in [`LICENSE`](LICENSE). Il testo del romanzo resta di proprietà dei rispettivi titolari dei diritti (vedi [`NOTICE.md`](NOTICE.md)).
