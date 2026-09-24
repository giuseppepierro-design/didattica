# Alan Turing: dalla crisi delle certezze alla nascita dell'informatica moderna

## 1. Introduzione

**Alan Mathison Turing (1912–1954)** è una delle figure fondamentali della storia dell'informatica.

Se **Charles Babbage** nell'Ottocento aveva immaginato una macchina programmabile capace di automatizzare il calcolo, Turing, circa un secolo dopo, affrontò una domanda ancora più profonda:

> **Che cosa significa, esattamente, calcolare?**

E soprattutto:

> **Esiste una procedura precisa che permetta di risolvere qualsiasi problema matematico?**

Per rispondere a domande di questo tipo, Turing elaborò nel 1936 un modello teorico estremamente semplice: la **macchina di Turing**.

Questa idea contribuì a fondare la moderna **teoria della computazione**.

Ma Turing non fu soltanto un matematico teorico.

Durante la **Seconda guerra mondiale** partecipò alla crittoanalisi britannica dei messaggi cifrati tedeschi. Successivamente contribuì allo sviluppo dei primi computer elettronici e fu tra i primi scienziati a interrogarsi seriamente sulla possibilità di costruire macchine capaci di mostrare comportamenti intelligenti.

Per comprendere Turing bisogna quindi inserirlo nel suo tempo.

La prima metà del Novecento fu infatti un periodo straordinario e drammatico, caratterizzato contemporaneamente da:

* due guerre mondiali;
* grandi trasformazioni politiche e sociali;
* nascita della meccanica quantistica;
* teoria della relatività;
* crisi dei fondamenti della matematica;
* sviluppo della logica matematica;
* nascita dell'elettronica;
* nuove tecnologie delle comunicazioni.

È un'epoca nella quale alcune delle certezze scientifiche e filosofiche dell'Ottocento vengono profondamente rimesse in discussione.

---

# 2. Dal mondo di Babbage al mondo di Turing

Charles Babbage era nato nel **1791**, durante la Rivoluzione industriale.

Alan Turing nacque nel **1912**, più di un secolo dopo.

Il mondo era completamente cambiato.

Nel XIX secolo le grandi innovazioni erano state soprattutto:

* macchina a vapore;
* ferrovie;
* grandi industrie;
* meccanizzazione della produzione;
* telegrafo.

All'inizio del XX secolo si erano invece sviluppati:

* elettricità;
* telefono;
* radio;
* automobili;
* aviazione;
* sistemi elettromeccanici;
* nuove reti di comunicazione.

Anche la scienza stava attraversando una trasformazione ancora più profonda.

Le idee tradizionali sullo spazio, sul tempo, sulla materia, sulla matematica e sulla possibilità stessa di conoscere e prevedere la realtà venivano messe in discussione.

Turing cresce quindi non soltanto nell'epoca delle nuove macchine, ma nell'epoca delle **nuove domande sui limiti della conoscenza**.

---

# 3. La grande fiducia ottocentesca nella scienza

Per capire il clima culturale del Novecento è utile partire dall'Ottocento.

I grandi successi della fisica classica avevano prodotto una straordinaria fiducia nella capacità della scienza di descrivere il mondo.

La meccanica di Newton permetteva di calcolare il movimento dei corpi.

Conoscendo:

* posizione;
* velocità;
* forze;

era possibile prevedere l'evoluzione futura di un sistema.

Si era quindi diffusa, almeno in alcune correnti del pensiero scientifico, un'immagine fortemente **deterministica** della natura.

In forma estremamente semplificata:

```text
CONDIZIONI INIZIALI
        +
LEGGI DELLA NATURA
        ↓
     CALCOLO
        ↓
   STATO FUTURO
```

L'universo poteva essere immaginato quasi come una gigantesca macchina governata da leggi matematiche.

Se conoscessimo perfettamente lo stato iniziale e tutte le leggi, potremmo, almeno idealmente, prevederne l'evoluzione.

---

# 4. Il Novecento e la crisi delle certezze

Nei primi decenni del Novecento questa immagine semplice comincia però a essere profondamente modificata.

In diversi settori emergono risultati sorprendenti.

Nella **fisica** nascono:

* la relatività;
* la meccanica quantistica.

Nella **matematica** emergono problemi riguardanti:

* i fondamenti della matematica;
* la logica;
* la dimostrazione;
* la completezza dei sistemi formali.

Non significa che la scienza entri in crisi nel senso di diventare meno affidabile.

Al contrario, vengono costruite teorie nuove e potentissime.

Ma emerge un'idea culturalmente importante:

> **la conoscenza scientifica può avere limiti strutturali che devono essere compresi e studiati.**

È in questo clima scientifico che matureranno anche i problemi affrontati da Alan Turing.

---

# 5. La rivoluzione della fisica

All'inizio del Novecento anche la fisica classica viene profondamente trasformata.

Con **Albert Einstein**, le idee tradizionali di spazio e tempo vengono ripensate attraverso la teoria della relatività.

Contemporaneamente nasce la **meccanica quantistica**, grazie al lavoro di numerosi scienziati, tra cui:

* Max Planck;
* Albert Einstein;
* Niels Bohr;
* Werner Heisenberg;
* Erwin Schrödinger;
* Max Born;
* Paul Dirac.

Il mondo microscopico si rivela molto diverso dall'immagine intuitiva costruita attraverso l'esperienza quotidiana.

---

# 6. La meccanica quantistica e i limiti della previsione classica

Nella fisica classica possiamo immaginare una particella come una piccola pallina che possiede in ogni momento una posizione e una velocità ben determinate.

La meccanica quantistica costringe a modificare profondamente questa immagine.

Nel **1927**, Werner Heisenberg formula il celebre **principio di indeterminazione**.

In termini molto semplificati, esistono coppie di grandezze fisiche, come posizione e quantità di moto, per le quali non è possibile attribuire simultaneamente valori arbitrariamente precisi nello stesso stato quantistico.

Inoltre, la teoria quantistica descrive molti risultati delle misurazioni attraverso **probabilità**.

Lo schema classico:

```text
CONOSCO PERFETTAMENTE IL PRESENTE
              ↓
CALCOLO ESATTAMENTE IL FUTURO
```

non può essere semplicemente trasferito al mondo quantistico.

Questo rappresenta una trasformazione concettuale enorme.

---

# 7. Attenzione: Turing non deriva dalla meccanica quantistica

Qui è importante fare una distinzione.

Non sarebbe corretto affermare:

> "Turing sviluppò la teoria della computazione a causa della meccanica quantistica."

Il problema affrontato da Turing nasce soprattutto dalla **matematica e dalla logica**.

Il percorso storico diretto è piuttosto:

```text
FONDAMENTI DELLA MATEMATICA
          ↓
        HILBERT
          ↓
         GÖDEL
          ↓
ENTSCHEIDUNGSPROBLEM
          ↓
        TURING
```

La meccanica quantistica rappresenta però un interessante **parallelismo storico e filosofico**.

Nella stessa epoca discipline differenti stanno scoprendo che alcune aspirazioni a una descrizione totalmente semplice, completa o meccanicamente prevedibile incontrano limiti profondi.

---

# 8. Il problema dei fondamenti della matematica

Tra la fine dell'Ottocento e l'inizio del Novecento i matematici si interrogano sulle fondamenta stesse della matematica.

Una domanda fondamentale è:

> **Possiamo costruire tutta la matematica partendo da un insieme preciso di assiomi e regole logiche?**

L'obiettivo era rendere il ragionamento matematico completamente rigoroso.

Una delle figure più importanti di questo programma fu il matematico tedesco:

# David Hilbert

Hilbert nutriva una grande fiducia nella possibilità di dare alla matematica fondamenta rigorose e sistematiche.

---

# 9. Una ricetta per la matematica?

Per capire il problema anche senza conoscere la logica matematica, possiamo utilizzare una semplice analogia.

Pensiamo a una **ricetta**.

Per preparare qualcosa possiamo avere istruzioni come:

```text
1. Prendi due fette di pane.
2. Metti il formaggio sulla prima.
3. Aggiungi il prosciutto.
4. Copri con la seconda fetta.
```

Non dobbiamo inventare ogni volta cosa fare.

Dobbiamo semplicemente seguire una serie precisa di istruzioni.

Qualcosa di simile accade quando eseguiamo un'addizione:

```text
  37
+ 25
----
  62
```

Seguiamo delle regole:

1. sommiamo 7 e 5;
2. scriviamo 2 e riportiamo 1;
3. sommiamo 3, 2 e il riporto;
4. otteniamo il risultato.

Cambiano i numeri, ma **la procedura rimane la stessa**.

Questa è l'idea fondamentale di un **algoritmo**.

---

# 10. Il sogno di una matematica completamente meccanizzabile

Possiamo allora porre una domanda molto più ambiziosa:

> Se possiamo creare una procedura per l'addizione, possiamo creare procedure precise per tutti i problemi matematici?

Immaginiamo una specie di gigantesco libro di istruzioni:

```text
PROBLEMA MATEMATICO
        ↓
     REGOLA 1
        ↓
     REGOLA 2
        ↓
     REGOLA 3
        ↓
       ...
        ↓
     RISPOSTA
```

Una persona potrebbe seguire queste istruzioni senza dover inventare nulla.

E allora nasce una conseguenza sorprendente:

> **Se le istruzioni sono completamente meccaniche, potrebbe eseguirle anche una macchina.**

Ma prima bisogna rispondere a una domanda fondamentale:

> **Che cosa significa esattamente "eseguire meccanicamente una procedura"?**

Questa sarà precisamente una delle grandi domande affrontate da Turing.

---

# 11. Gödel: un primo grande limite

Prima del lavoro di Turing avviene qualcosa di straordinario.

Nel **1931**, il matematico e logico **Kurt Gödel** pubblica i suoi celebri **teoremi di incompletezza**.

In termini molto semplificati, Gödel dimostra che sistemi formali sufficientemente potenti da esprimere una certa quantità di aritmetica incontrano limiti fondamentali.

In particolare, sotto appropriate condizioni, esistono enunciati che il sistema non può né dimostrare né confutare al proprio interno.

Questo risultato modifica profondamente le aspettative riguardanti una completa formalizzazione della matematica.

Non significa:

> "La matematica non funziona."

E nemmeno:

> "Non possiamo conoscere nulla con certezza."

Significa qualcosa di molto più preciso e interessante:

> **anche un sistema matematico costruito con regole perfettamente rigorose può avere limiti interni.**

---

# 12. Da Gödel a Turing

Pochi anni dopo arriva Alan Turing.

Nel **1936**, a soli 24 anni, pubblica:

*On Computable Numbers, with an Application to the Entscheidungsproblem*.

Turing affronta un problema collegato al famoso **Entscheidungsproblem**, il "problema della decisione".

In maniera molto semplificata, la domanda era:

> Possiamo costruire una procedura meccanica generale che permetta di stabilire, per ogni formula del sistema logico considerato, se essa è dimostrabile?

Per affrontare il problema, Turing deve prima chiarire una questione apparentemente semplice:

> **Che cosa significa "procedura meccanica"?**

O, utilizzando il linguaggio moderno:

> **Che cos'è davvero un algoritmo?**

---

# 13. L'esperimento mentale di Turing

Immaginiamo una persona estremamente precisa che debba eseguire un calcolo.

Questa persona dispone di:

* carta;
* una matita;
* alcuni simboli;
* un insieme preciso di istruzioni.

La persona non deve necessariamente comprendere il significato profondo del problema.

Deve semplicemente:

```text
LEGGERE UN SIMBOLO
        ↓
APPLICARE UNA REGOLA
        ↓
SCRIVERE UN SIMBOLO
        ↓
SPOSTARSI
        ↓
RIPETERE
```

Turing si domanda:

> Possiamo descrivere matematicamente una macchina ideale capace di fare esattamente questo?

Da questa domanda nasce la:

# macchina di Turing

---

# 14. La macchina di Turing

La macchina di Turing è un modello teorico estremamente semplice.

Possiamo immaginarla composta da:

* un **nastro** diviso in celle;
* simboli scritti nelle celle;
* una **testina** capace di leggere e scrivere;
* un insieme di **stati**;
* una serie di **regole**.

```text
             testina
                ↓
... | 0 | 1 | 1 | 0 | _ | _ | ...
             NASTRO
```

La macchina può:

1. leggere un simbolo;
2. scriverne un altro;
3. spostarsi a destra o a sinistra;
4. cambiare stato;
5. ripetere il procedimento.

La macchina non è "intelligente".

Non comprende quello che sta facendo.

Segue semplicemente delle **regole**.

---

# 15. Nasce il concetto di computabilità

Con questa macchina teorica Turing riesce a rendere molto più precisa l'idea di calcolo automatico.

Il percorso diventa:

```text
PROBLEMA
   ↓
ALGORITMO
   ↓
SEQUENZA DI OPERAZIONI ELEMENTARI
   ↓
ESECUZIONE MECCANICA
   ↓
RISULTATO
```

Se un problema può essere risolto attraverso una procedura algoritmica di questo tipo, diciamo che è **computabile**.

Nasce così uno dei concetti fondamentali dell'informatica:

# COMPUTABILITÀ

La domanda non è più soltanto:

> "Quanto velocemente possiamo effettuare questo calcolo?"

La domanda precedente e ancora più fondamentale diventa:

> **"Esiste un algoritmo capace di risolvere questo problema?"**

---

# 16. La grande sorpresa: non tutto è computabile

La risposta di Turing conduce a un risultato sorprendente.

Esistono problemi per i quali **non può esistere un algoritmo generale che fornisca sempre la risposta**.

Uno degli esempi più famosi è il:

# problema dell'arresto — Halting Problem

Immaginiamo di avere un programma qualsiasi.

Vogliamo costruire un secondo programma capace di esaminarlo e rispondere sempre correttamente alla domanda:

> "Questo programma prima o poi terminerà oppure continuerà per sempre?"

Potremmo desiderare qualcosa del genere:

```text
PROGRAMMA
    ↓
ANALIZZATORE UNIVERSALE
    ↓
┌────────────┬─────────────┐
│ TERMINERÀ  │ NON TERMINERÀ│
└────────────┴─────────────┘
```

Turing dimostra che **non può esistere un algoritmo generale capace di rispondere sempre correttamente a questa domanda per qualsiasi programma e input**.

È un limite teorico.

Non dipende dal fatto che il nostro computer sia troppo lento.

Non dipende dalla quantità di memoria.

Non basta costruire un computer un milione di volte più potente.

Il problema è più profondo:

**l'algoritmo generale richiesto non esiste.**

---

# 17. Gödel, Turing e la meccanica quantistica: un parallelismo

Possiamo ora osservare qualcosa di affascinante.

Nel giro di pochi decenni emergono limiti fondamentali in discipline differenti.

## Nella fisica

La meccanica quantistica modifica profondamente l'idea classica di previsione e introduce una descrizione intrinsecamente probabilistica di molti fenomeni.

## Nella matematica

Gödel mostra che sistemi formali sufficientemente potenti hanno limiti interni rispetto a ciò che può essere dimostrato al loro interno.

## Nella computazione

Turing mostra che esistono problemi che nessun algoritmo generale può risolvere.

Possiamo rappresentare schematicamente questo clima scientifico:

```text
             PRIMA METÀ DEL NOVECENTO
                       │
          ┌────────────┼────────────┐
          │            │            │
       FISICA      MATEMATICA   COMPUTAZIONE
          │            │            │
     QUANTISTICA      GÖDEL        TURING
          │            │            │
          └────────────┼────────────┘
                       ↓
             SCOPERTA DI LIMITI
               FONDAMENTALI
```

Questi risultati **non dicono la stessa cosa** e non derivano direttamente l'uno dall'altro.

Ma appartengono a un clima scientifico nel quale diventa sempre più importante comprendere non soltanto:

> **"Che cosa possiamo conoscere e calcolare?"**

ma anche:

> **"Quali sono i limiti fondamentali di ciò che possiamo conoscere, dimostrare o calcolare?"**

---

# 18. Una rivoluzione filosofica

Questo cambiamento ha anche un'importante dimensione filosofica.

L'Ottocento aveva conosciuto enormi successi scientifici e tecnologici.

All'inizio del Novecento emerge però un'immagine più complessa.

La scienza non consiste soltanto nell'accumulare conoscenze.

Può anche scoprire **i limiti delle proprie procedure**.

Possiamo quindi vedere una trasformazione culturale:

```text
DOMANDA CLASSICA

"Come possiamo conoscere tutto?"
             ↓

NUOVA DOMANDA

"Che cosa possiamo conoscere,
dimostrare o calcolare,
e quali sono i limiti?"
```

È importante non interpretare tutto questo come una sconfitta della scienza.

È quasi il contrario.

La scienza diventa abbastanza potente da riuscire a studiare rigorosamente **anche i propri limiti**.

---

# 19. La macchina universale: verso il computer moderno

Turing fece poi un altro passo fondamentale.

Invece di immaginare una macchina diversa per ogni algoritmo, possiamo immaginare una macchina capace di **leggere la descrizione di un'altra macchina e simularne il comportamento**.

Nasce così il concetto di:

# Universal Turing Machine

La **macchina universale di Turing**.

In forma semplificata:

```text
          MACCHINA UNIVERSALE
                  ↑
                  │
        ┌─────────┴─────────┐
        │                   │
    PROGRAMMA              DATI
```

La stessa macchina può comportarsi in modi completamente differenti a seconda delle istruzioni che riceve.

Questa idea anticipa un principio fondamentale del computer moderno:

> **non abbiamo bisogno di costruire una macchina diversa per ogni problema: possiamo utilizzare la stessa macchina e cambiare il programma.**

---

# 20. Da Babbage a Turing

Possiamo ora comprendere meglio il collegamento tra Charles Babbage e Alan Turing.

### Babbage

Babbage vive nell'epoca della **Rivoluzione industriale**.

Le macchine stanno automatizzando il lavoro fisico.

La sua grande intuizione è:

> **Se una macchina può automatizzare il lavoro manuale, perché non può automatizzare anche il calcolo?**

Nasce l'idea della **macchina programmabile**.

### Turing

Turing vive invece nell'epoca della grande rivoluzione scientifica del Novecento.

La sua domanda è più astratta:

> **Che cosa significa esattamente calcolare?**

E poi:

> **Esistono limiti a ciò che una macchina può calcolare?**

Nasce la **teoria della computazione**.

```text
RIVOLUZIONE INDUSTRIALE
          ↓
       BABBAGE
          ↓
AUTOMATIZZARE IL CALCOLO
          ↓
MACCHINA PROGRAMMABILE
          ↓
          ↓
CRISI DEI FONDAMENTI DELLA MATEMATICA
          ↓
        TURING
          ↓
DEFINIRE IL CALCOLO
          ↓
COMPUTABILITÀ
          ↓
LIMITI DEL CALCOLO
```

---

# 21. Dalla rivoluzione scientifica alla guerra

Mentre matematica e fisica attraversavano queste profonde rivoluzioni teoriche, l'Europa entrava in uno dei periodi più drammatici della propria storia.

Turing era nato nel 1912.

Due anni dopo iniziò la **Prima guerra mondiale**.

Negli anni Trenta assistette:

* alla crisi economica;
* all'ascesa del nazismo;
* alla diffusione dei regimi totalitari;
* alla crescente tensione internazionale.

Nel **1939** la Germania invase la Polonia.

Gran Bretagna e Francia entrarono in guerra.

Cominciava la **Seconda guerra mondiale**.

Le idee matematiche e le nuove tecnologie avrebbero assunto improvvisamente un'importanza militare enorme.

---

# 22. La guerra dell'informazione

La Seconda guerra mondiale non fu combattuta soltanto attraverso:

* carri armati;
* navi;
* aerei;
* artiglieria.

Fu anche una gigantesca:

# guerra dell'informazione

Gli eserciti dovevano trasmettere continuamente:

* ordini;
* coordinate;
* movimenti delle truppe;
* informazioni sui convogli;
* operazioni navali;
* strategie.

Ma un messaggio trasmesso via radio poteva essere intercettato dal nemico.

Era quindi necessario **cifrarlo**.

La Germania utilizzava diversi sistemi crittografici, tra cui la celebre macchina:

# Enigma

---

# 23. Enigma e la crittografia simmetrica

Enigma era una macchina elettromeccanica utilizzata per cifrare e decifrare messaggi.

In maniera semplificata:

```text
MESSAGGIO
    ↓
ENIGMA + CONFIGURAZIONE SEGRETA
    ↓
TESTO CIFRATO
    ↓
TRASMISSIONE RADIO
    ↓
ENIGMA + CONFIGURAZIONE CORRETTA
    ↓
MESSAGGIO ORIGINALE
```

Possiamo considerarla un esempio storico di **crittografia simmetrica**.

Mittente e destinatario dovevano infatti condividere le informazioni necessarie per impostare correttamente le macchine.

La sicurezza dipendeva quindi dalla segretezza della configurazione utilizzata.

---

# 24. Turing a Bletchley Park

Durante la guerra Turing lavorò a **Bletchley Park**, il principale centro britannico di crittoanalisi.

Qui lavoravano insieme:

* matematici;
* linguisti;
* crittografi;
* ingegneri;
* operatori;
* personale militare.

Il problema era enorme.

Le configurazioni possibili di Enigma erano talmente numerose che verificarle manualmente sarebbe stato estremamente difficile.

Ancora una volta ritroviamo un problema tipicamente informatico:

> **Come trasformare un enorme lavoro logico e ripetitivo in qualcosa che possa essere automatizzato?**

Turing contribuì allo sviluppo dei metodi utilizzati contro Enigma, in particolare nel settore delle comunicazioni navali tedesche.

Contribuì inoltre allo sviluppo della **Bombe britannica**, una macchina elettromeccanica utilizzata per accelerare la ricerca delle possibili configurazioni di Enigma.

Il lavoro non fu naturalmente opera del solo Turing.

Fu il risultato di una gigantesca collaborazione britannica e alleata e si basò anche sui fondamentali risultati ottenuti precedentemente dai crittoanalisti polacchi.

---

# 25. Dalla teoria alla pratica

Possiamo vedere un interessante passaggio nella vita di Turing.

Negli anni Trenta la sua domanda era:

> **Che cosa può essere calcolato?**

Durante la guerra emerge una seconda domanda:

> **Come possiamo eseguire abbastanza velocemente un numero enorme di operazioni?**

La distinzione è fondamentale.

Un problema può essere teoricamente risolvibile ma richiedere una quantità enorme di tempo.

In una situazione reale, invece, il risultato deve arrivare **quando è ancora utile**.

```text
PROBLEMA
   ↓
È RISOLVIBILE?
   ↓
      SÌ
   ↓
MA QUANTO TEMPO SERVE?
```

Questa distinzione anticipa un'altra grande area dell'informatica:

**lo studio della complessità e dell'efficienza degli algoritmi.**

---

# 26. Dopo la guerra: costruire realmente i computer

Terminata la guerra, Turing partecipò direttamente allo sviluppo dei computer elettronici.

Lavorò al **National Physical Laboratory**, dove progettò l'**ACE — Automatic Computing Engine**.

Successivamente lavorò all'Università di Manchester, uno dei principali centri britannici nello sviluppo dei primi computer.

Il percorso della sua vita scientifica è quindi straordinario:

```text
1936
TEORIA DELLA COMPUTAZIONE
        ↓
1939–1945
CRITTOANALISI E AUTOMAZIONE
        ↓
DOPOGUERRA
COMPUTER ELETTRONICI
        ↓
1950
INTELLIGENZA ARTIFICIALE
```

Turing parte da una domanda apparentemente astratta della logica matematica e arriva direttamente alla nascita del computer moderno.

---

# 27. Possono pensare le macchine?

Nel **1950**, Turing pubblicò un altro celebre articolo:

*Computing Machinery and Intelligence*.

L'articolo si apre con una domanda destinata a diventare famosissima:

> **Can machines think?**

> **Possono pensare le macchine?**

Turing si rese però conto che definire esattamente la parola "pensare" era estremamente difficile.

Propose quindi di trasformare la domanda filosofica in qualcosa di più concreto e osservabile.

Da questa idea deriva quello che oggi chiamiamo:

# Test di Turing

In forma semplificata, immaginiamo una persona che conversa attraverso messaggi testuali con due interlocutori che non può vedere.

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

La questione diventa allora se il comportamento linguistico della macchina possa risultare indistinguibile da quello umano nelle condizioni dell'esperimento.

Ancora una volta Turing utilizza una strategia caratteristica:

**trasformare una domanda filosofica difficile in un problema formulato attraverso regole più precise.**

---

# 28. La persecuzione di Alan Turing

La vita personale di Turing ebbe un finale tragico.

Nel Regno Unito dell'epoca i rapporti omosessuali tra uomini erano criminalizzati.

Nel **1952** Turing fu perseguito penalmente per una relazione con un uomo.

Accettò un trattamento ormonale come alternativa alla detenzione.

Nel **1954**, a soli 41 anni, morì per avvelenamento da cianuro. La morte fu registrata come suicidio, anche se successivamente sono state discusse interpretazioni alternative delle circostanze.

Decenni dopo, il trattamento subito da Turing è stato pubblicamente riconosciuto come un'ingiustizia.

Nel **2013** ricevette un perdono reale postumo.

---

# 29. Cronologia: Turing dentro il suo tempo

| Anno          | Storia, scienza e vita di Turing                                                |
| ------------- | ------------------------------------------------------------------------------- |
| **1900**      | Planck introduce l'ipotesi dei quanti                                           |
| **1905**      | Einstein pubblica lavori fondamentali, tra cui quello sulla relatività speciale |
| **1912**      | Nasce Alan Turing                                                               |
| **1914–1918** | Prima guerra mondiale                                                           |
| **anni 1920** | Sviluppo della moderna meccanica quantistica                                    |
| **1927**      | Principio di indeterminazione di Heisenberg                                     |
| **1931**      | Gödel pubblica i teoremi di incompletezza                                       |
| **1936**      | Turing pubblica il lavoro sulla computabilità                                   |
| **1939**      | Inizia la Seconda guerra mondiale in Europa                                     |
| **1939–1945** | Turing lavora nella crittoanalisi britannica                                    |
| **anni 1940** | Rapido sviluppo delle macchine elettroniche di calcolo                          |
| **1945–1946** | Turing sviluppa il progetto dell'ACE                                            |
| **1948**      | Turing si trasferisce all'Università di Manchester                              |
| **1950**      | Pubblica *Computing Machinery and Intelligence*                                 |
| **1952**      | Viene perseguito per omosessualità                                              |
| **1954**      | Muore Alan Turing                                                               |
| **2013**      | Perdono reale postumo                                                           |

---

# 30. Perché Turing è fondamentale per l'informatica?

L'importanza di Turing non deriva da una singola invenzione.

Il suo lavoro tocca quasi tutte le grandi domande che accompagneranno la nascita dell'informatica.

### Algoritmi

Contribuisce a dare una definizione rigorosa dell'idea di procedimento automatico.

### Computabilità

Permette di distinguere ciò che può essere calcolato algoritmicamente da ciò che non può esserlo.

### Limiti della computazione

Dimostra che esistono problemi per i quali nessun algoritmo generale può esistere.

### Macchina universale

Mostra teoricamente che una singola macchina può eseguire algoritmi differenti se riceve istruzioni differenti.

### Programmazione

Contribuisce all'idea fondamentale che il comportamento di una macchina possa dipendere dal programma che essa esegue.

### Computer elettronici

Dopo la guerra partecipa concretamente alla progettazione dei primi computer britannici.

### Crittografia e crittoanalisi

Durante la Seconda guerra mondiale applica matematica, logica e automazione a problemi reali di enorme complessità.

### Intelligenza artificiale

È tra i primi scienziati a discutere in modo sistematico la possibilità che una macchina possa mostrare comportamenti considerati intelligenti.

---

# 31. Da Babbage a Turing: dalla forza all'informazione

Possiamo infine osservare un'evoluzione storica molto più ampia.

## Rivoluzione industriale

La domanda fondamentale era:

> Come possiamo utilizzare le macchine per amplificare la **forza fisica** dell'uomo?

```text
UOMO → MACCHINA → PIÙ FORZA
```

## Babbage

La domanda diventa:

> Possiamo utilizzare una macchina per automatizzare il **calcolo**?

```text
UOMO → MACCHINA → CALCOLO AUTOMATICO
```

## Turing

La domanda diventa ancora più generale:

> Quali procedimenti possono essere eseguiti automaticamente?

```text
PROBLEMA
   ↓
ALGORITMO
   ↓
COMPUTAZIONE
   ↓
INFORMAZIONE
```

E subito dopo compare una domanda ancora più profonda:

> **Esistono limiti a ciò che può essere automatizzato?**

La risposta di Turing è:

**sì.**

---

# 32. La lezione più importante di Turing

La grandezza di Turing consiste anche nell'aver contribuito a mostrare che il computer non è semplicemente una **calcolatrice molto veloce**.

È qualcosa di molto più generale.

Un computer è una macchina capace di:

1. rappresentare informazioni;
2. ricevere istruzioni;
3. eseguire algoritmi;
4. trasformare informazioni secondo regole;
5. produrre risultati.

Ma Turing ci insegna contemporaneamente qualcosa di ancora più profondo:

> **non tutto ciò che possiamo formulare come problema può necessariamente essere risolto da un algoritmo.**

Il computer è quindi una macchina estremamente potente, ma non onnipotente.

---

# 33. Conclusione: Turing e il secolo dei limiti

Alan Turing appartiene a una delle stagioni più straordinarie della storia della scienza.

Nel giro di pochi decenni:

* Einstein modifica la nostra concezione di spazio e tempo;
* la meccanica quantistica modifica profondamente la concezione classica della previsione fisica;
* Gödel scopre limiti fondamentali dei sistemi formali;
* Turing scopre limiti fondamentali della computazione;
* l'elettronica rende possibile costruire macchine di calcolo sempre più potenti;
* la Seconda guerra mondiale accelera drammaticamente lo sviluppo della crittografia, delle comunicazioni e delle tecnologie di calcolo.

Questi sviluppi non sono tutti direttamente collegati tra loro.

Ma insieme raccontano una trasformazione culturale fondamentale del Novecento.

La domanda scientifica non è più soltanto:

> **"Che cosa possiamo conoscere?"**

Diventa anche:

> **"Quali sono i limiti di ciò che possiamo conoscere, dimostrare, prevedere e calcolare?"**

Turing porta questa domanda nel cuore dell'informatica.

Babbage aveva immaginato che una macchina potesse automatizzare il calcolo.

Turing va oltre e domanda:

> **Che cos'è un calcolo?**

> **Che cosa può essere calcolato?**

> **Esistono problemi che nessuna macchina algoritmica potrà risolvere?**

Da queste domande nasce una parte fondamentale dell'informatica teorica moderna.

Ed è forse questo l'aspetto più affascinante della storia di Turing:

**la teoria del computer nasce, almeno in parte, non dalla costruzione di una macchina, ma da una domanda sui limiti della matematica e del ragionamento automatico.**
