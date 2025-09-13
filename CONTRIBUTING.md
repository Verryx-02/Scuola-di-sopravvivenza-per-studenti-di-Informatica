<div align="center"> 

# Come contribuire al progetto

</div>
In questo file troverai tutto ciò che ti serve sapere per contribuire al progetto Scuola di sopravvivenza per studenti di informatica. Anche il più piccolo dei contributi è ben visto, purché sia sensato. 

### Se NON sai usare GitHub

1. Scrivimi a [verryx_github.untaken971@passinbox.com] inviandomi:
    - Correzioni o suggerimenti
    - Nuove sezioni
    - Errori che hai trovato
    - La tua esperienza se vuoi condividerla
    - Qualunque altra cosa che vorresti inserire nella guida
       
2. Scrivi nei gruppi di Informatica specificando che è per la guida di sopravvivenza

### Se sai usare GitHub (o vuoi imparare)

1. Fai un **fork** della repository
2. Clona il progetto sul tuo pc
```
git clone https://github.com/Verryx-02/Scuola-di-sopravvivenza-per-studenti-di-Informatica
```
   
3. Crea un nuovo branch:
```
git checkout -b nome-della-tua-modifica
```

4. Fai le tue modifiche (vedi sezione importante qui sotto)
5. Aggiungi le modifiche all'area di staging:
```
git add .
```
6. Commit:
```
git commit -m "Descrizione delle modifiche"
```
7. Push:
```
git push origin nome-della-tua-modifica
```
8. Apri una **Pull Request**

## ⚠️ IMPORTANTE: Modifiche ai file

### Cosa modificare
- **Modifica SOLO i file .tex** (Volume1.tex, Volume2.tex, Volume3.tex)
- README.md e altri file di documentazione
- **NON modificare mai i PDF**

### Perché non modificare i PDF
I file PDF (Volume1.pdf, Volume2.pdf, Volume3.pdf) vengono compilati automaticamente dai file LaTeX. 

**Problemi se modifichi i PDF:**
- Non posso vedere le differenze nelle review
- Le tue modifiche verranno sovrascritte quando ricompilo
- Rallenta il processo di review

### Come funziona il processo
1. Tu modifichi il file .tex appropriato
2. Io compilo e aggiorno il PDF corrispondente dopo il merge
3. Tutti vedono le tue modifiche nel PDF finale

### Se non sai usare LaTeX
Se non conosci LaTeX ma vuoi contribuire:
- Apri una **Issue** descrivendo la modifica
- Ti aiuterò io a implementarla nel file .tex
- In alternativa, inviami un'email con i dettagli

##  Tipi di Contributi Benvenuti

### Cosa accetto sempre

- **Correzioni di errori** (grammatica, link rotti, informazioni obsolete)
- **Aggiornamenti** su date, procedure, software
- **Nuovi consigli pratici** basati su esperienza diretta
- **Miglioramenti della chiarezza** (riscrivere parti confuse)
- **Nuove sezioni** pertinenti al corso di Informatica UNIUD

### Cosa valuto caso per caso

- Consigli su corsi di altre università
- Sezioni molto lunghe che potrebbero andare nei volumi futuri
- Opinioni controverse senza giustificazione

### Cosa NON accetto

- Pubblicità o spam
- Consigli su come copiare agli esami
- Informazioni false o fuorvianti
- Linguaggio offensivo o discriminatorio
- Critiche gratuite verso docenti o studenti

## Linee Guida per i Contenuti

### Stile di scrittura

- usa un **tono** amichevole ma diretto, come l'originale
- Usa la **seconda persona** ("tu", "ti consiglio")
- Includi sempre **esempi** concreti quando possibile
- Sii trasparente e **onesto** su pro e contro dei tuoi consigli

### Formattazione LaTeX

Se modifichi il file .tex, usa:

- `\section{}`, `\subsection{}` e `\subsubsection{}` coerentemente
- `\href{URL}{Testo}` per i link esterni
- `\textbf{}` per il grassetto
- `quote` per i consigli importanti
- `itemize` per le liste
- Compila localmente per verificare che non ci siano errori di sintassi

### Aggiornamenti informativi

Quando aggiungi informazioni che possono diventare obsolete:

- Indica la data: "aggiornato ad agosto 2025"
- Specifica la fonte quando possibile
- Usa un linguaggio che non diventi rapidamente datato

## Processo di Review

### Cosa controllo

1. **Accuratezza**: Le informazioni sono corrette?
2. **Pertinenza**: È utile per studenti di Informatica UNIUD?
3. **Chiarezza**: È scritto in modo comprensibile?
4. **Coerenza**: Si integra bene con il resto del documento?
5. **Sintassi LaTeX**: Il codice compila senza errori?

### Tempi di risposta

Dipendono molto dal tempo che ho a disposizione e da quando vedo la notifica. Potrei metterci 30 minuti come 3 settimane.

## Idee per Contributi

Non sai da dove iniziare? Ecco alcune idee:

### Aggiornamenti necessari

- [ ] Verificare tutti i link esterni
- [ ] Aggiornare informazioni su software e app
- [ ] Aggiornare prezzi e modelli di PC consigliati

### Nuove sezioni potenziali

- [ ] Come gestire l'ansia da esame
- [ ] Consigli per studenti lavoratori
- [ ] Come scegliere la magistrale
- [ ] Gestione del tempo durante la sessione
- [ ] Come prepararsi per il tirocinio

### Miglioramenti di sezioni esistenti

- [ ] Più esempi pratici nella sezione studio
- [ ] Alternative ai Mac per studenti con budget limitato

## Suggerimenti per Nuovi Contributori

### Se è la tua prima volta

1. **Leggi tutto il documento** prima di proporre grandi cambiamenti
2. **Chiedi se non sei sicuro**: Meglio una domanda in più che un lavoro rifatto
3. **Usa i canali Whatsapp**: Gli altri studenti possono aiutarti
4. **Inizia piccolo**: Una piccola correzione è meglio di una grande modifica mal fatta

### Come scrivere buone descrizioni

**Buono**: "Corretto errore di grammatica in Volume1.tex, sezione 'Scelta del PC'"  
**Cattivo**: "Fix"

**Buono**: "Aggiunta sezione su come gestire l'ansia pre-esame in Volume1.tex basata su esperienza personale"  
**Cattivo**: "Roba nuova"

**Buono**: "Aggiornati prezzi MacBook in Volume1.tex, sezione hardware"  
**Cattivo**: "Modificato Volume1.pdf"

## Utilizzo degli Issue Templates

Per segnalazioni e proposte, usa i template delle Issues:
- **Segnala un errore**: Per correzioni immediate
- **Sezione non aggiornata**: Per informazioni obsolete  
- **Proponi nuova sezione**: Per nuovi contenuti
- **Altro**: Per tutto il resto

I template ti guidano a fornire tutte le informazioni necessarie per una risposta rapida.

## Codice di Condotta
Voglio che tutti si sentano benvenuti, indipendentemente da:

- Livello di esperienza in programmazione
- Background scolastico
- Provenienza geografica
- Identità di genere, orientamento, età, ecc

### Comportamenti inaccettabili

- Linguaggio offensivo o discriminatorio
- Pubblicazione di informazioni private senza consenso

## Contatti

- **Maintainer principale**: [@Verryx-02](https://github.com/Verryx-02)
- **Discord**: Server Informatica UNIUD
- **Email**: [verryx_github.untaken971@passinbox.com]

## Licenza

Contribuendo a questo progetto, accetti che i tuoi contributi siano rilasciati sotto la stessa licenza del progetto originale.

---

**Ricorda**: Questa guida esiste per aiutare gli studenti di Informatica. Ogni contributo, per quanto piccolo, può fare la differenza per qualcuno!

## Riconoscimenti

Tutti i contributori verranno menzionati nei ringraziamenti del documento principale. Se preferisci rimanere anonimo, fammelo sapere.

Grazie per aver letto fino a qui e per voler contribuire!: