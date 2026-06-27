# Presentazione delle Meccaniche di un Gioco da Tavolo Educativo

**Nome dello Studente:** Arianna Berrafato, Claudio Martelli, Daniele Rizzo
**Titolo del Gioco:** Antologia Forense

---

## 1. Meccaniche Principali del Gioco

### 1.1 Descrizione delle Meccaniche Scelte

Il gioco combina un sistema di carte azione a risorse limitate (Interroga, Esamina Oggetto, Suggerimento, Accusa) con una narrazione generativa gestita da un LLM nel ruolo di Game Master. I giocatori spendono carte per compiere azioni narrative e ricevono ricompense in carte quando formulano deduzioni corrette.

### 1.2 Motivazione della Scelta delle Meccaniche

Le carte razionano le interazioni, rendendo ogni scelta deliberata e strategicamente pesata. L'LLM garantisce risposte narrative fedeli al testo e personalizzate alle azioni del gruppo. La ricompensa tramite carte per le intuizioni crea un loop di rinforzo direttamente ancorato alla qualità del ragionamento.

---

## 2. Modalità di Interazione dei Giocatori

### 2.1 Tipo di Interazione

Cooperativa: il gruppo delibera collettivamente le azioni da compiere, condivide le deduzioni e decide insieme quando usare una carta e quale.

### 2.2 Motivazione della Modalità di Interazione

La cooperazione è funzionale al contesto educativo: stimola il dialogo, la negoziazione e la costruzione condivisa del senso.

---

## 3. Bilanciamento tra Casualità e Strategia

### 3.1 Descrizione del Bilanciamento

La variabilità deriva dall'imprevedibilità delle risposte dell'LLM (che adatta tono e dettaglio alle domande) e dall'ordine in cui il gruppo sceglie di esplorare la storia. La strategia domina: quali carte usare, quando, su quali oggetti o personaggi.

### 3.2 Motivazione del Bilanciamento

L'assenza di casualità meccanica sposta il peso interamente sulle scelte cognitive. Questo è coerente con l'obiettivo educativo: l'abilità di deduzione, non la fortuna, determina il progresso.

---

## 4. Considerazioni Aggiuntive

### 4.1 Integrazione delle Meccaniche con Obiettivi Educativi

Le carte Esamina Oggetto promuovono l'attenzione ai dettagli testuali; le Interroga stimolano la comprensione dei personaggi e delle motivazioni; il Suggerimento introduce il ragionamento per indizi; la carta Accusa richiede una sintesi argomentata. Ogni meccanica corrisponde a una competenza di lettura analitica.

### 4.2 Feedback e Riflessioni Ricevute

A testo annotato, la chatbot LLM non era ancora in linea con quelle che erano le aspettative del gruppo circa il corretto proseguio del gioco:

- Si perdeva tra le svariate informazioni del testo annotato sacrificando tag cardine, proponendo ad ogni nuova chat generata uno scenario che si discostava troppo da quello precedente.
- Non riusciva a standardizzare le porzioni di testo annotato pensate per essere narrativo-suggestive da quelle interattive.

Entra, qui, in gioco il cronogramma: un documento apposito scritto in markdown pensato per orientare in maniera rafforzativa, sintetica e puntuale la cronistoria ludico-narrativa del gioco. Il cronogramma è suddiviso in "scene", ogni scena in "introduzione narrativa" e "turni", con la prima che funge da intermezzo narrativo-suggestivo tra una scena e l'altra, mentre i turni sono i veri e propri momenti interattivi, lo spazio in cui la narrazione del master si squarcia e le pagine sbiadite del romanzo chiedono ai giocatori di essere ricondotte all'antica completezza.

Lo schema del Cronogramma è stato ideato affinché riflettesse una logica a cascata, che ricalcasse in maniera netta una priorità cronologica e settoriale rispetto a come la chatbot LLM dovesse gestire le scene e proporre ai giocatori di vivere i turni.

---

*Documento originale: `ANTOLOGIA_FORENSE_Meccaniche_di_Gioco.docx`*
