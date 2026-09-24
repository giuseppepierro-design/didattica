# Alan Turing: dalla matematica alla nascita dell'informatica moderna

## 1. Introduzione

**Alan Mathison Turing (1912–1954)** è una delle figure fondamentali della storia dell'informatica.

Se **Charles Babbage** nell'Ottocento aveva immaginato una macchina programmabile capace di automatizzare il calcolo, Turing, circa un secolo dopo, affrontò una domanda ancora più profonda:

> **Che cosa significa, esattamente, calcolare?**

Turing non partì inizialmente dalla necessità di costruire una macchina fisica. Il suo problema era soprattutto **matematico e logico**.

Voleva capire quali problemi potessero essere risolti attraverso una sequenza precisa di operazioni e quali, invece, non potessero esserlo.

Per rispondere inventò nel 1936 un modello teorico estremamente semplice: la **macchina di Turing**.

Quell'idea contribuì a fornire le fondamenta teoriche dell'informatica moderna.

Ma Turing non fu soltanto un teorico.

Durante la **Seconda guerra mondiale** partecipò alla crittoanalisi britannica dei messaggi cifrati tedeschi. Successivamente contribuì allo sviluppo dei primi computer elettronici e fu tra i primi scienziati a interrogarsi seriamente sulla possibilità di costruire macchine dotate di quella che oggi chiamiamo **intelligenza artificiale**.

Per comprendere Turing bisogna quindi inserirlo nel suo tempo: un'epoca segnata contemporaneamente da una straordinaria rivoluzione scientifica e da due guerre mondiali.

---

# 2. Un uomo della prima metà del Novecento

Alan Turing nacque a Londra nel **1912**.

Il mondo nel quale crebbe era profondamente diverso da quello di Babbage.

Babbage aveva vissuto nell'epoca della macchina a vapore e della prima industrializzazione.

Turing nacque invece in una società nella quale erano ormai diffusi:

* elettricità;
* telefono;
* radio;
* automobili;
* grandi industrie;
* sistemi meccanici ed elettromeccanici;
* moderne reti di comunicazione.

La scienza stava inoltre attraversando trasformazioni rivoluzionarie.

Nei primi decenni del Novecento erano nate o si erano sviluppate:

* la **relatività**;
* la **meccanica quantistica**;
* la moderna logica matematica;
* nuovi studi sui fondamenti della matematica.

Il periodo storico di Turing fu però anche estremamente drammatico.

La sua vita si colloca tra:

* la **Prima guerra mondiale (1914–1918)**;
* la crisi economica e politica degli anni Trenta;
* l'ascesa dei regimi totalitari;
* la **Seconda guerra mondiale (1939–1945)**;
* l'inizio della Guerra fredda.

Scienza, matematica e tecnologia stavano diventando sempre più importanti non soltanto per la ricerca, ma anche per l'industria, le comunicazioni e la guerra.

---

# 3. Il grande problema della matematica

Per capire veramente perché Turing sia importante per l'informatica dobbiamo partire da un problema che, apparentemente, non ha nulla a che vedere con i computer.

All'inizio del Novecento molti matematici cercavano di costruire fondamenta estremamente rigorose per tutta la matematica.

Una delle grandi figure di questo movimento fu il matematico tedesco **David Hilbert**.

L'idea generale era molto ambiziosa:

> Possiamo trasformare il ragionamento matematico in un procedimento completamente rigoroso, basato su regole precise?

In altre parole:

se abbiamo un problema matematico, possiamo immaginare una procedura composta da una sequenza finita e precisa di operazioni che ci permetta di ottenere la risposta?

Oggi chiameremmo una procedura di questo tipo un:

# algoritmo

---

# 4. Ma che cos'è veramente un algoritmo?

Gli algoritmi esistevano naturalmente molto prima di Turing.

Un algoritmo può essere pensato come una sequenza precisa di istruzioni.

Per esempio:

```text
1. Prendi due numeri.
2. Confrontali.
3. Se il primo è maggiore del secondo, scambiali.
4. Continua secondo determinate regole.
5. Produci il risultato.
```

Ma negli anni Trenta nasceva una domanda più profonda:

> **Che cosa significa dire che un procedimento può essere eseguito "meccanicamente"?**

Immaginiamo una persona che esegue un calcolo molto lungo seguendo istruzioni estremamente precise.

Questa persona:

* legge un simbolo;
* applica una regola;
* scrive un simbolo;
* passa alla fase successiva;
* continua fino al risultato.

Non deve necessariamente comprendere il significato profondo del problema.

Deve semplicemente **seguire correttamente le istruzioni**.

Turing ebbe un'intuizione straordinaria:

> Proviamo a descrivere matematicamente questo processo.

---

# 5. La macchina di Turing

Nel **1936**, a soli 24 anni, Turing pubblicò il celebre lavoro *On Computable Numbers, with an Application to the Entscheidungsproblem*.

In questo lavoro introdusse quella che oggi chiamiamo **macchina di Turing**.

Non era principalmente il progetto di un computer da costruire.

Era una **macchina teorica**, estremamente semplice, inventata per capire che cosa significhi effettuare un calcolo attraverso regole precise.

La macchina può essere immaginata come composta da:

* un **nastro** suddiviso in celle;
* simboli scritti nelle celle;
* una **testina** capace di leggere e scrivere;
* un insieme di **stati**;
* una serie di **regole**.

Schema semplificato:

```text
       testina
          ↓
... | 0 | 1 | 1 | 0 | _ | _ | ...
        NASTRO
```

La testina può:

1. leggere il simbolo presente;
2. scrivere un nuovo simbolo;
3. spostarsi a destra o a sinistra;
4. cambiare stato;
5. ripetere il procedimento.

Sembra una macchina quasi banale.

Eppure questa semplicità nasconde un'idea potentissima.

---

# 6. Dal ragionamento alla macchina

Turing stava cercando di catturare l'essenza di un procedimento algoritmico.

Possiamo rappresentare il suo ragionamento così:

```text
PROBLEMA
   ↓
PROCEDURA PRECISA
   ↓
SEQUENZA DI ISTRUZIONI
   ↓
ESECUZIONE MECCANICA
   ↓
RISULTATO
```

Se un problema può essere risolto attraverso una procedura di questo tipo, possiamo dire che è **computabile**.

Nasce così uno dei concetti fondamentali dell'informatica:

# computabilità

La domanda non è più semplicemente:

> Quanto velocemente possiamo effettuare un calcolo?

La domanda diventa:

> **Questo problema può essere risolto da un algoritmo?**

---

# 7. Una scoperta sorprendente: esistono problemi non calcolabili

Uno dei risultati più profondi del lavoro di Turing fu mostrare che esistono limiti fondamentali a ciò che può essere calcolato algoritmicamente.

Non tutti i problemi possono essere risolti da una procedura automatica generale.

Un esempio fondamentale è quello che oggi chiamiamo:

# Halting Problem — problema dell'arresto

In termini semplificati, possiamo porre questa domanda:

> Possiamo costruire un algoritmo universale che, ricevuti un qualsiasi programma e i suoi dati, stabilisca sempre se quel programma prima o poi terminerà oppure continuerà per sempre?

Turing dimostrò che **un algoritmo generale di questo tipo non può esistere**.

Questo risultato è importantissimo.

Significa che l'informatica possiede dei **limiti teorici fondamentali**.

Non importa quanto potente sia il computer.

Non importa quanta memoria possieda.

Non importa quanto velocemente possa eseguire le istruzioni.

Esistono problemi per i quali **non esiste un algoritmo generale capace di fornire sempre la risposta richiesta**.

---

# 8. La macchina universale: un'idea vicinissima al computer moderno

Turing fece poi un passo ancora più importante.

Invece di immaginare una macchina diversa per ogni algoritmo, possiamo immaginare una macchina capace di **leggere la descrizione di un'altra macchina e simularne il comportamento**.

Nasce così il concetto di:

# Universal Turing Machine

La **macchina universale di Turing**.

L'idea può essere semplificata così:

```text
          MACCHINA UNIVERSALE
                 ↑
                 │
       ┌─────────┴─────────┐
       │                   │
   PROGRAMMA              DATI
```

La stessa macchina fisica può eseguire compiti completamente diversi semplicemente ricevendo istruzioni differenti.

Questo principio è centrale nel computer moderno.

---

# 9. Da Babbage a Turing

A questo punto possiamo vedere un collegamento molto interessante con Charles Babbage.

Babbage aveva immaginato una **macchina fisica programmabile**.

Turing sviluppò una teoria matematica generale della **computazione**.

Possiamo semplificare il percorso storico:

```text
BABBAGE
   ↓
Una macchina può eseguire
automaticamente operazioni
   ↓
MACCHINA PROGRAMMABILE
   ↓
TURING
   ↓
Che cosa significa eseguire
un procedimento algoritmico?
   ↓
TEORIA DELLA COMPUTAZIONE
```

Babbage anticipa soprattutto il **computer come macchina**.

Turing contribuisce a definire il **computer come concetto matematico**.

---

# 10. Il programma come informazione

L'idea della macchina universale porta a una conseguenza fondamentale.

Un programma può essere rappresentato attraverso simboli.

Ma anche i dati vengono rappresentati attraverso simboli.

Quindi:

```text
DATI       → informazione rappresentata
PROGRAMMA  → informazione rappresentata
```

La macchina può quindi trattare sia i dati sia le istruzioni come informazione codificata.

Questa idea sarà fondamentale nello sviluppo dei computer moderni.

Un computer non deve essere ricostruito fisicamente ogni volta che vogliamo cambiare problema.

Possiamo mantenere la stessa macchina e cambiare il:

**software**.

---

# 11. Arriva la Seconda guerra mondiale

Pochi anni dopo il lavoro teorico di Turing, l'Europa precipitò nella **Seconda guerra mondiale**.

Nel 1939 la Germania invase la Polonia e Gran Bretagna e Francia entrarono in guerra.

Le comunicazioni militari erano fondamentali.

Gli eserciti dovevano continuamente trasmettere informazioni riguardanti:

* movimenti delle truppe;
* operazioni navali;
* rifornimenti;
* ordini;
* strategie.

Naturalmente questi messaggi dovevano essere protetti.

La Germania utilizzava diversi sistemi crittografici, tra i quali la famosa macchina:

# Enigma

---

# 12. Enigma e la guerra dell'informazione

Enigma era una macchina elettromeccanica utilizzata per cifrare messaggi.

Un messaggio normale veniva trasformato in un testo apparentemente incomprensibile.

Per esempio, schematicamente:

```text
MESSAGGIO
   ↓
 ENIGMA
   ↓
TESTO CIFRATO
   ↓
TRASMISSIONE RADIO
```

Chi riceveva il messaggio, disponendo delle impostazioni appropriate, poteva decifrarlo.

Il problema per gli Alleati era quindi riuscire a ricostruire le impostazioni utilizzate dai tedeschi.

Il numero delle configurazioni possibili era enorme.

Provare manualmente tutte le possibilità sarebbe stato estremamente difficile.

Ancora una volta compare un problema familiare:

> **Come utilizzare delle macchine per automatizzare un enorme numero di operazioni logiche?**

---

# 13. Turing a Bletchley Park

Durante la guerra Turing lavorò a **Bletchley Park**, il principale centro britannico di crittoanalisi.

Qui lavoravano:

* matematici;
* linguisti;
* esperti di crittografia;
* ingegneri;
* operatori;
* personale militare.

Turing ebbe un ruolo molto importante nello sviluppo dei metodi utilizzati contro Enigma, in particolare per le comunicazioni navali tedesche.

Contribuì inoltre allo sviluppo della **Bombe britannica**, una macchina elettromeccanica utilizzata per accelerare la ricerca delle possibili impostazioni di Enigma.

È importante evitare una semplificazione frequente:

> Turing **non lavorò da solo** e non fu l'unico responsabile della decifrazione di Enigma.

Il successo fu il risultato di un enorme lavoro collettivo britannico e alleato e si basò anche sui fondamentali risultati ottenuti precedentemente dai crittoanalisti polacchi.

Turing fu però una delle figure scientifiche più importanti di questo sforzo.

---

# 14. Dalla teoria alla necessità pratica

La guerra accelerò enormemente lo sviluppo delle tecnologie di calcolo.

Prima della guerra Turing si era chiesto:

> Che cosa può essere calcolato?

Durante la guerra il problema diventava anche:

> Come possiamo eseguire enormi quantità di operazioni abbastanza velocemente da ottenere un'informazione quando è ancora utile?

Questo introduce una distinzione fondamentale.

Un problema può essere teoricamente risolvibile, ma può richiedere una quantità enorme di tempo.

Nella vita reale, e soprattutto durante una guerra, il **tempo di calcolo** diventa essenziale.

Si comincia così a intravedere un altro grande settore dell'informatica:

**lo studio dell'efficienza degli algoritmi.**

---

# 15. Attenzione: Bombe, Enigma e Colossus non sono la stessa cosa

Nella storia divulgativa dell'informatica questi elementi vengono talvolta confusi.

È utile distinguerli.

**Enigma** era una macchina tedesca utilizzata per cifrare messaggi.

La **Bombe** era una macchina elettromeccanica utilizzata dai britannici per aiutare a determinare le impostazioni di Enigma.

**Colossus**, invece, era un sistema elettronico sviluppato a Bletchley Park soprattutto per contribuire alla decifrazione di un diverso sistema di comunicazioni tedesco, associato ai cifrari Lorenz.

Turing fu centrale nel lavoro su Enigma e contribuì più in generale alla cultura scientifica e crittanalitica di Bletchley Park, ma **Colossus non fu progettato da Turing**.

Il principale progettista di Colossus fu **Tommy Flowers**.

Questa distinzione è importante per comprendere correttamente la storia.

---

# 16. Dopo la guerra: costruire realmente i computer

Terminata la guerra, Turing partecipò direttamente allo sviluppo dei computer elettronici.

Lavorò al **National Physical Laboratory (NPL)**, dove progettò l'**ACE — Automatic Computing Engine**.

L'obiettivo non era più soltanto studiare teoricamente una macchina universale.

Adesso si trattava di:

> **costruire realmente computer elettronici programmabili.**

Successivamente Turing lavorò anche all'Università di Manchester, uno dei centri più importanti nello sviluppo dei primi computer britannici.

La sua vita scientifica attraversa quindi due fasi straordinarie:

```text
ANNI '30
Teoria della computazione
        ↓
ANNI '40
Crittoanalisi e macchine
        ↓
DOPOGUERRA
Computer elettronici
```

---

# 17. Una nuova domanda: le macchine possono pensare?

Turing non si fermò al calcolo.

Nel **1950** pubblicò un altro celebre articolo:

*Computing Machinery and Intelligence*.

L'articolo iniziava con una domanda destinata a diventare famosissima:

> **Can machines think?**

> Possono pensare le macchine?

Turing si rese però conto che la parola "pensare" era estremamente difficile da definire.

Propose quindi di sostituire la domanda con un esperimento più concreto.

Da questa idea nasce quello che oggi chiamiamo:

# Test di Turing

---

# 18. Il Test di Turing

In una versione semplificata, immaginiamo una persona che conversa attraverso messaggi testuali con due interlocutori che non può vedere.

Uno è umano.

L'altro è una macchina.

```text
               PERSONA
                  │
          comunicazione testuale
             ┌────┴────┐
             │         │
           UMANO    MACCHINA
```

Se durante la conversazione la persona non riesce in modo affidabile a distinguere la macchina dall'essere umano, la macchina mostra un comportamento linguistico che, nel contesto del test, può essere confrontato con quello umano.

Il punto importante non era necessariamente fornire una definizione definitiva di "intelligenza".

Turing cercava soprattutto di trasformare una domanda filosofica molto vaga in una domanda **operativa e osservabile**.

Questo lavoro è considerato uno dei testi fondamentali nella storia dell'**intelligenza artificiale**.

---

# 19. Un'intuizione straordinariamente moderna

Turing aveva compreso una conseguenza fondamentale del computer programmabile.

Se possediamo una macchina universale, non abbiamo necessariamente bisogno di costruire una macchina fisicamente diversa per ogni attività.

Possiamo cambiare il programma.

```text
                COMPUTER
                    │
       ┌────────────┼────────────┐
       ↓            ↓            ↓
   CALCOLARE     GIOCARE      ELABORARE
                              LINGUAGGIO
       │            │            │
       └────────────┴────────────┘
                    ↓
             stesso hardware
           programmi differenti
```

Questa è una delle idee più potenti dell'informatica.

Lo stesso computer può diventare:

* calcolatrice;
* elaboratore di testi;
* sistema di comunicazione;
* simulatore;
* videogioco;
* strumento scientifico;
* sistema di intelligenza artificiale.

La sua funzione non è determinata soltanto dalla sua struttura fisica.

È determinata anche dal **programma che esegue**.

---

# 20. La persecuzione di Alan Turing

La storia personale di Turing ebbe un finale tragico.

Nel Regno Unito dell'epoca i rapporti omosessuali tra uomini erano criminalizzati.

Nel **1952**, Turing fu perseguito penalmente per la sua relazione con un uomo.

Per evitare la detenzione accettò un trattamento ormonale.

Due anni dopo, nel **1954**, morì a soli **41 anni** per avvelenamento da cianuro. La morte fu registrata come suicidio, anche se nel tempo sono state discusse interpretazioni alternative delle circostanze.

Decenni dopo il trattamento subito da Turing è stato pubblicamente riconosciuto come un'ingiustizia.

Nel 2013 ricevette un **perdono reale postumo**.

La sua vicenda è quindi anche una testimonianza del contrasto tra l'enorme contributo che un individuo può dare alla società e il modo in cui la stessa società può perseguitarlo sulla base delle leggi e dei pregiudizi della propria epoca.

---

# 21. Babbage e Turing: due tappe della stessa storia

Possiamo ora collegare i due personaggi.

## Charles Babbage

Vive nell'epoca della **Rivoluzione industriale**.

Vede le macchine automatizzare il lavoro fisico e immagina:

> Perché non automatizzare anche il calcolo?

Nasce l'idea della **macchina programmabile**.

---

## Alan Turing

Vive nell'epoca della matematica moderna, delle comunicazioni e dei primi sistemi elettronici.

Si domanda:

> Che cosa significa realmente calcolare?

Nasce una teoria matematica della **computazione**.

Possiamo rappresentare il percorso:

```text
RIVOLUZIONE INDUSTRIALE
          ↓
       BABBAGE
          ↓
MACCHINA PROGRAMMABILE
          ↓
          ↓
LOGICA E MATEMATICA DEL '900
          ↓
        TURING
          ↓
TEORIA DELLA COMPUTAZIONE
          ↓
MACCHINA UNIVERSALE
          ↓
COMPUTER ELETTRONICO
          ↓
INFORMATICA MODERNA
```

---

# 22. Babbage e Turing a confronto

| Charles Babbage          | Alan Turing                                                 |
| ------------------------ | ----------------------------------------------------------- |
| 1791–1871                | 1912–1954                                                   |
| Rivoluzione industriale  | Rivoluzione scientifica e tecnologica del Novecento         |
| Macchine meccaniche      | Teoria matematica + macchine elettromeccaniche/elettroniche |
| Difference Engine        | Macchina di Turing                                          |
| Analytical Engine        | Macchina universale di Turing                               |
| Automatizzare il calcolo | Definire matematicamente il calcolo                         |
| Macchina programmabile   | Computabilità                                               |
| Schede perforate         | Programma rappresentato simbolicamente                      |
| Precursore del computer  | Fondatore dell'informatica teorica                          |

I due contributi sono diversi ma complementari.

**Babbage si domanda come costruire una macchina capace di calcolare.**

**Turing si domanda che cosa significhi, in senso matematico, che qualcosa possa essere calcolato.**

---

# 23. Cronologia essenziale

| Anno          | Evento                                                                          |
| ------------- | ------------------------------------------------------------------------------- |
| **1912**      | Nasce Alan Turing                                                               |
| **1914–1918** | Prima guerra mondiale                                                           |
| **1936**      | Turing pubblica il lavoro sulla computabilità e introduce la macchina di Turing |
| **1939**      | Inizia la Seconda guerra mondiale in Europa                                     |
| **1939–1945** | Turing lavora nella crittoanalisi britannica a Bletchley Park                   |
| **anni '40**  | Sviluppo accelerato delle macchine elettroniche di calcolo                      |
| **1945–1946** | Turing sviluppa il progetto dell'ACE                                            |
| **1948**      | Turing si trasferisce all'Università di Manchester                              |
| **1950**      | Pubblica *Computing Machinery and Intelligence*                                 |
| **1952**      | Viene perseguito per omosessualità                                              |
| **1954**      | Muore Alan Turing                                                               |
| **2013**      | Perdono reale postumo                                                           |

---

# 24. Perché Turing è così importante per l'informatica?

L'importanza di Turing non deriva da una singola invenzione.

Il suo contributo attraversa quasi tutti i problemi fondamentali che caratterizzeranno la nascita dell'informatica.

### 1. Algoritmi

Turing contribuisce a formalizzare matematicamente il concetto di procedimento automatico.

### 2. Computabilità

Permette di distinguere ciò che può essere calcolato algoritmicamente da ciò che non può esserlo.

### 3. Macchina universale

Mostra teoricamente che una sola macchina può simulare moltissime altre macchine semplicemente cambiando le istruzioni.

### 4. Programmazione

Rafforza l'idea fondamentale della separazione tra la macchina fisica e il programma che essa esegue.

### 5. Computer elettronici

Dopo la guerra partecipa concretamente alla progettazione dei primi computer britannici.

### 6. Crittografia e crittoanalisi

Durante la Seconda guerra mondiale applica matematica, logica e automazione a problemi reali di enorme complessità.

### 7. Intelligenza artificiale

È tra i primi a discutere in maniera scientifica la possibilità che una macchina possa mostrare comportamenti consider
