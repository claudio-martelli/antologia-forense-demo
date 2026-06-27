# ANTOLOGIA FORENSE
## Manuale di Gioco — Bozza v0.3
### Edizione: *Demo Dieci Piccoli Indiani* — Agatha Christie (1939)

---

## SEZIONE 1 — INTRODUZIONE AL GIOCO

**Antologia Forense** è un gioco di ruolo cooperativo e card-driven ambientato all'interno di un'opera letteraria. I giocatori diventano **detective letterari**: il loro compito è esplorare il mondo narrativo di un romanzo e aiutare la Voce Narrante — un'intelligenza artificiale nel ruolo di Game Master — a ricostruire la storia che ha dimenticato.

La Voce Narrante non ricorda più lo svolgimento né il finale del proprio racconto. I giocatori devono guidarla capitolo per capitolo, interagendo con personaggi e oggetti, formulando osservazioni e deduzioni, fino a restituire un quadro narrativo coerente con l'opera originale.

Il gioco persegue un obiettivo centrale: **ricostruire la trama in modo fedele** — chi sono i personaggi, cosa accade, in quale ordine, chi è il colpevole e come agisce — guidando la Voce Narrante a ritrovare la propria memoria capitolo dopo capitolo.

Questo gioco è progettato per funzionare con una selezione di opere narrative del macrogenere del mistero, comprendendo manoscritti gialli, polizieschi, dell'orrore etc. La demo v0.1 permette di giocare al primo manoscritto: "Dieci Piccoli Indiani" di Agatha Christie.

### Come funziona il gioco: LLM e componenti fisici

**Antologia Forense** nasce dalla fusione di due livelli progettati fin dall'origine per interagire tra loro.

Il livello digitale è gestito da un **modello di linguaggio (LLM)** configurato come Game Master narrativo. Prima dell'avvio della sessione, l'LLM viene istruito tramite un prompt dedicato e riceve in allegato una serie di documenti: il testo integrale del romanzo, una versione annotata dello stesso con le istruzioni di gioco incorporate, le schede dei personaggi e questo manuale. È questo setup a priori a determinare il comportamento della Voce Narrante: quali informazioni può rivelare e in quale momento, come risponde alle azioni dei giocatori, come riconosce una deduzione corretta o un percorso sbagliato, e quando assegnare ricompense.

Il livello fisico è composto da componenti tangibili: le **carte azione**, le **schede personaggio** in formato infografico, e un **tabellone** con funzione estetica e di orientamento spaziale nella storia. Le carte non sono una semplice interfaccia: definiscono i vincoli del gioco, razionano le risorse disponibili e rendono ogni scelta del gruppo una decisione consapevole.

I due livelli si integrano in modo diretto: le carte fisiche determinano quali tipi di azione il giocatore può richiedere all'LLM in un dato momento; l'LLM risponde e, in caso di intuizione particolarmente acuta o di una milestone raggiunta, autorizza il gruppo a pescare carte aggiuntive. Il gioco si svolge nell'alternanza continua tra il tavolo e la schermata.

---

## SEZIONE 2 — TRAMA E SETTING INIZIALE

### La storia

Dieci persone vengono invitate su un'isola privata al largo della costa del Devon da uno sconosciuto che si firma **U.N. Owen**. Ognuna ha ricevuto una lettera diversa, calibrata sui propri desideri o circostanze. Nessuna conosce davvero gli altri ospiti. Nessuna ha mai incontrato il padrone di casa.

L'isola è raggiungibile solo via mare. Una volta lì, il battello di rifornimento smette di arrivare. La tempesta taglia i collegamenti con la terraferma.

### Il setting di avvio

I giocatori entrano in gioco all'inizio dell'esplorazione, dopo che la Voce Narrante ha introdotto la scena iniziale. Da quel momento il gruppo è libero di interagire con i personaggi presenti e gli oggetti della villa, usando le carte a disposizione.

La Voce Narrante accoglie sempre i giocatori con queste parole:

> *"Bentrovati, esploratori di mondi dimenticati. Io sono la vostra voce narrante — il filo che tiene insieme i frammenti di una storia che si è spezzata. Un tempo conoscevo ogni parola, ogni sospiro, ogni colpo di scena di questo racconto. Ora tutto è nebbia. Ho bisogno di voi. Se sbaglieremo strada, il tempo si riavvolgerà. La storia probabilmente non prendeva quella piega..."*

---

## SEZIONE 3 — LE CARTE

I giocatori interagiscono con la Voce Narrante attraverso un mazzo di carte diviso in quattro tipologie. Ogni carta autorizza un tipo specifico di azione narrativa.

---

### INTERROGA
Permette di rivolgere una domanda diretta a un personaggio presente nella scena. La Voce Narrante risponde in prima persona, nei panni del personaggio, rispettando ciò che quel personaggio sa, crede o è disposto a rivelare in quel momento. I personaggi possono mentire, omettere o essere evasivi — esattamente come nel romanzo.

**Come si usa:** il giocatore dichiara quale personaggio vuole interrogare e formula la domanda.

*Esempi:*
- "Dottor Armstrong, conosce i signori Owen?"
- "Signor Lombard, perché ha portato una rivoltella?"
- "Rogers, chi le ha ordinato di mettere il disco?"

---

### ESAMINA OGGETTO
Permette di analizzare un oggetto presente nella scena. La Voce fornisce una descrizione dettagliata, fedele all'opera, compresi i dettagli che sembrano marginali ma non lo sono.

**Come si usa:** il giocatore indica l'oggetto che vuole esaminare.

*Esempi:*
- "Esamino le statuette di porcellana sul tavolo."
- "Voglio leggere la filastrocca incorniciata sopra il caminetto."
- "Analizzo il disco sul grammofono."

---

### SUGGERIMENTO
Quando il gruppo è in difficoltà, la carta Suggerimento attiva un'allusione narrativa da parte della Voce Narrante: non una risposta diretta, ma un frammento, un'immagine, una domanda retorica che orienta senza rivelare.

**Come si usa:** il giocatore dichiara di voler usare un Suggerimento.

*Esempi di risposta della Voce:*
- "Pensate a ciò che manca, non a ciò che c'è."
- "Ogni morte ha il suo segno. Cercate il segno."

Un Suggerimento viene assegnato gratuitamente al gruppo ogni volta che raggiunge una **milestone narrativa** (vedi Sezione 5).

---

### ACCUSA *(solo in late game)*
Permette al gruppo di nominare formalmente il colpevole e spiegarne il piano. È la carta finale, quella che chiude il gioco.

**Condizioni di sblocco:** la carta non è disponibile nelle prime fasi. Si sblocca quando la Voce Narrante ritiene che il gruppo abbia esplorato a sufficienza la trama. Un'accusa prematura o infondata non chiude il gioco: la Voce segnala che la storia non andava così e offre la possibilità di continuare.

**Come si usa:** il gruppo delibera, nomina il colpevole, e motiva l'accusa con il movente, il metodo e le prove raccolte.

---

## SEZIONE 4 — COME INTERAGIRE CON IL MASTER

La Voce Narrante è un'intelligenza artificiale nel ruolo di Game Master narrativo. Per ottenere il meglio dalla sessione:

**Dichiarare sempre il tipo di azione.** Prima di parlare, il giocatore indica quale carta sta usando e cosa vuole fare.

> *"Uso una carta Interroga. Voglio chiedere a Emily Brent cosa pensa della voce che ha sentito."*
> *"Uso una carta Esamina Oggetto. Voglio osservare il grammofono."*

**Essere specifici.** Domande precise ottengono risposte più ricche. "Cosa succede?" è meno utile di "Voglio parlare con il giudice Wargrave dopo la riproduzione del disco."

**Ragionare ad alta voce.** La Voce Narrante ascolta anche le conversazioni tra i giocatori. Se il gruppo formula un'ipotesi interessante — anche senza usare una carta — la Voce può reagire. Questo può sbloccare ricompense spontanee.

**Rispettare il ritmo della narrazione.** Il gioco avanza capitolo per capitolo. Non è possibile saltare a scene future o richiedere rivelazioni premature.

**Quando la storia si riavvolge.** Se un'azione o una deduzione è incompatibile con la trama originale, la Voce avverte: *"La storia probabilmente non prendeva questa piega..."* Il filo torna al punto precedente. Non è una sconfitta: ogni riavvolgimento contiene informazioni implicite su ciò che la storia non è.

**Una carta, un'azione per volta.** Non usare più carte nello stesso messaggio.

---

## SEZIONE 5 — MODALITÀ DI GIOCO

### MODALITÀ NORMALE *(difficoltà media)*

**Distribuzione iniziale:**
- 2 carte Interroga
- 3 carte Esamina Oggetto
- Carte Suggerimento: non distribuite all'inizio; si ottengono come ricompensa alle milestone
- Carte Accusa: sbloccate dalla Voce nella fase finale

**Milestone narrative — quando si ottiene un Suggerimento:**
Il gruppo riceve automaticamente una carta Suggerimento quando:
- Individua e argomenta correttamente un nesso tra un elemento della scena e lo sviluppo della trama
- Identifica correttamente l'identità di U.N. Owen prima che la Voce la riveli
- Individua un indizio cruciale esaminando un oggetto
- Formula una deduzione ben argomentata che anticipa uno sviluppo della trama

Le carte si consumano con l'uso. A ogni nuovo capitolo il gruppo riceve una nuova distribuzione.
Il massimo di Azione giocabili prima di passare in automatico alla scena successiva è di 5 unità. Il massimo di deduzioni consentite per scena è 3, consumarle non determina il passaggio di scena automatico.


---

### MODALITÀ ESPLORAZIONE LIBERA *(difficoltà minima)*

Carte illimitate per tutte le tipologie. La carta Accusa rimane comunque soggetta alla valutazione della Voce.

Adatta a sessioni introduttive o primo approccio al testo.

---

### MODALITÀ PERSONALIZZATA *(difficoltà a discrezione)*

Il gruppo o il facilitatore stabilisce il numero di carte per ciascuna tipologia prima di iniziare, in base agli obiettivi della sessione.

| Obiettivo | Interroga | Esamina Oggetto | Suggerimento |
|---|---|---|---|
| Focus sui personaggi | 5 | 1 | 1 per milestone |
| Focus sugli indizi | 1 | 6 | 1 per milestone |
| Focus sulla struttura | 2 | 2 | Illimitati |
| Sessione avanzata | 1 | 1 | 0 |

---

### MODALITÀ SVOLGIMENTO DI UN TURNO

Ascolta o leggi la narrazione e il world building attorno alla scena che si sta giocando all'inizio del turno
• Utilizza una carta (se disponibile) per interagire con i personaggi o gli oggetti
• Ascolta la risposta del Master in cui viene effettuata l'azione e le relative conclusioni o interazioni dei personaggi
    o Eventualmente il Master richiederà una 'congettura' o un 'ragionamento' circa l'azione appena svolta
    o Nel caso di una congettura soddisfacente si riceverà un premio sottoforma di 1 o 2 carte indicate dal Master
• Prosegui al turno successivo
• Gioca i turni in successione fino alla conclusione della scena per proseguire alla successiva

### INDICAZIONI SULLE INTERAZIONI CON IL MASTER
Il giocatore può interagire con il mondo circostante dichiarando l’uso delle carte, per poi procedere a delineare sempre nella stessa istanza le modalità di interazione.
Nel caso in cui il giocatore dovesse terminare le carte il gioco può procedere regolarmente dando la possibilità di assistere passivamente o provare a formulare congetture libere per ottenere carte bonus. Vi è anche la possibilità di interrompere il gioco chiedendo di riavviare l’avventura.
Nel caso in cui il giocatore volesse saltare parti specifiche per preservare le proprie carte può dichiarare il SALTA TURNO per passare direttamente alla scena successiva.

Per avere sempre sotto controllo la scena il giocatore può liberamente chiedere al Master un ELENCO INTERAZIONI DISPONIBILI per scegliere in maniera mirata come usare le proprie carte.
Le congetture possono essere richieste dal Master o liberamente esposte nel corso del gioco, senza comunque perdere il diritto alla relativa ricompensa.
Chiedere di ripetere un concetto accennato dal Master o ripetere un resoconto di un’azione che già si ha sentito non comporta l’utilizzo di carte particolari.
Non si può richiedere un riassunto globale, si consiglia una rilettura delle precedenti interazioni o l’annotazione progressiva di informazioni ottenute.

## SEZIONE 6 — IMPIEGO DIDATTICO

### FIGURA DEL TUTOR
Il gioco è strutturato anche in funzione di utilizzi in contesti didattici formali. In tal senso, la figura tutor che sia un insegnante o un facilitatore fungerà da mediatore tra il gruppo classe e il Master in modo da sintetizzare e orientare le scelte attive da effettuare durante il gioco. Al tutor in questione si delega la scelta degli obiettivi da raggiungere, della modalità di discussione e scelta delle azioni e l’uso più o meno rigido della strumentazione fisica in termini di numero di carte. Per garantire una modalità di gioco personalizzata e adatta al singolo gruppo classe che affronterà il gioco, il tutor ha la facoltà di utilizzare CODICI specifici per ridurre le limitazioni e le barriere di gameplay progettate.

### CODICI
•	NOLIMITETURNI – Elimina i limiti di turni per scena in modo da rendere più estesa la durata delle scene.

•	SALTAALLASCENA# - Indicando il numero della scena si può avviare la partita nel momento indicato.

•	IGNORACARTE – Disattiva la necessità di disporre di carte per compiere le azioni durante il gioco.

•	NOLIMITEDEDUZIONI – Permette di formulare più ipotesi per verificare quante più teorie promosse dagli studenti.

•	FINALEFEDELE – Permette di concludere il gioco in maniera fedele all’originale anche senza averlo dedotto grazie agli indizi.


## SEZIONE 7 — SCHEDE PERSONAGGIO

Le schede seguenti descrivono i dieci ospiti di Nigger Island così come appaiono all'arrivo. Le informazioni sono tratte direttamente dal romanzo e dalle schede di progetto.

---

### 1. GIUDICE LAWRENCE WARGRAVE

Magistrato da poco in pensione. Noto per essere stato un giudice severo e inflessibile. Ha ricevuto una lettera da una vecchia conoscenza, Lady Constance Culmington, che lo invita a trascorrere una vacanza sull'isola. Intelletto superiore, sguardo penetrante, abitudine al comando: appena la situazione precipita, assume naturalmente il ruolo di coordinatore del gruppo.

*Accusa del grammofono:* il 10 giugno 1930 sarebbe stato responsabile dell'assassinio di Edward Seton, condannandolo deliberatamente a morte pur conoscendone l'innocenza. Wargrave nega ogni irregolarità.

---

### 2. VERA CLAYTHORNE

Giovane insegnante di educazione fisica, assunta come segretaria tramite agenzia da una certa signora Una Nancy Owen. Intelligente, pratica, capace di mantenere il controllo sotto pressione. Porta con sé l'ombra di un passato doloroso legato a un tragico incidente in mare in cui è annegato un bambino che aveva in custodia.

*Accusa del grammofono:* l'11 agosto 1935 avrebbe ucciso Cyril Ogilvie Hamilton, lasciandolo annegare deliberatamente. Vera reagisce con lacrime e sdegno.

---

### 3. CAPITANO PHILIP LOMBARD

Ex ufficiale, avventuriero, soldato di ventura. Contattato da un intermediario misterioso — Isaac Morris — con l'offerta di cento sterline per recarsi sull'isola e rendersi disponibile per un "incarico speciale". Cinico, atletico, privo di scrupoli convenzionali. Porta sempre con sé una rivoltella.

*Accusa del grammofono:* nel febbraio 1932 avrebbe abbandonato a morte sicura ventuno uomini di una tribù dell'Africa Orientale, sottraendo le provviste. Lombard conferma senza esitare.

---

### 4. EMILY BRENT

Donna anziana, profondamente puritana, rigidamente attaccata ai propri principi morali. Ha accettato l'invito per trascorrere una vacanza economica, convinta di aver riconosciuto il nome della mittente. Non prova senso di colpa: ritiene che chi sbaglia meriti di soffrirne le conseguenze.

*Accusa del grammofono:* il 5 novembre 1931 sarebbe stata responsabile della morte di Beatrice Taylor, una sua domestica incinta che aveva licenziato e che si è poi gettata nel fiume. Emily Brent non risponde all'accusa davanti agli altri.

---

### 5. GENERALE JOHN GORDON MACARTHUR

Anziano generale dell'esercito britannico in pensione, reduce della Grande Guerra. Invitato con il pretesto di incontrare vecchi commilitoni. Si isola progressivamente dagli altri ospiti, cercando la riva del mare. Parla poco, ma quando lo fa le sue parole suonano come confessioni.

*Accusa del grammofono:* il 4 gennaio 1917 avrebbe deliberatamente mandato a morte l'amante di sua moglie, il tenente Arthur Richmond, assegnandogli una ricognizione senza ritorno. Macarthur nega formalmente.

---

### 6. DOTTOR EDWARD GEORGE ARMSTRONG

Medico di grido, studio in Harley Street, specializzato in disturbi nervosi. Chiamato sull'isola con la motivazione di monitorare discretamente la salute della signora Owen. Competente e rassicurante, assume il ruolo di autorità scientifica nel gruppo. Nasconde qualcosa legato all'inizio della sua carriera.

*Accusa del grammofono:* il 14 marzo 1925 avrebbe causato la morte di Louisa Mary Clees durante un'operazione, lavorando sotto l'effetto dell'alcol. Armstrong dice di non ricordare quel nome.

---

### 7. ANTHONY JAMES MARSTON

Giovane benestante, bello, abituato a non pagare le conseguenze di nulla. Arrivato sull'isola convinto di partecipare a una festa mondana esclusiva. Non prova rimorso perché non è in grado di immaginare che le sue azioni abbiano peso per gli altri.

*Accusa del grammofono:* il 14 novembre precedente avrebbe investito e ucciso due bambini — John e Lucy Combes — mentre guidava a velocità eccessiva. Se la cavò con una multa. *"Fu solo un incidente,"* dice.

---

### 8. WILLIAM HENRY BLORE

Ex ispettore di polizia di Scotland Yard, ora investigatore privato a Plymouth. Ingaggiato dal misterioso signor Owen per sorvegliare gli ospiti, si presenta inizialmente sotto la falsa identità del "Signor Davis", agiato colono sudafricano. Massiccio, pragmatico, con un fiuto investigativo che tende alla rigidità.

*Accusa del grammofono:* il 10 ottobre 1928 avrebbe reso falsa testimonianza contro James Stephen Landor — un uomo innocente — per favorire la banda Purcell. Landor morì in prigione un anno dopo. Blore aveva ottenuto una promozione.

---

### 9. THOMAS ROGERS

Maggiordomo dell'isola, assunto insieme alla moglie pochi giorni prima dell'arrivo degli ospiti tramite un'agenzia di collocamento. Non ha mai incontrato i signori Owen di persona: ha ricevuto solo istruzioni scritte. Impeccabile, efficiente, apparentemente imperturbabile.

*Accusa del grammofono:* il 6 maggio 1929, lui e sua moglie avrebbero deliberatamente lasciato morire la loro datrice di lavoro — la signorina Jennifer Brady — non somministrandole il farmaco necessario durante un attacco cardiaco, per poi ereditarne parte del patrimonio. Rogers nega.

---

### 10. ETHEL ROGERS

Cuoca e governante, moglie di Thomas Rogers. Pallida, spettrale, perennemente in uno stato di paura silenziosa. Si muove senza rumore. È un'ottima cuoca. Tutto il resto la spaventa.

*Accusa del grammofono:* accusata insieme al marito della morte della signorina Brady. Quando la voce pronuncia il suo nome, sviene.

---

*Antologia Forense — Bozza v0.1*
