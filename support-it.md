# Supporto — JacArrow

**Ultimo aggiornamento:** 2026-08-22
**Versione coperta:** v1.0+
**Contatto:** galge.vender.0a@icloud.com

---

## Aiuto rapido

### Come registro una volée?

1. Apri JacArrow → tocca **Nuova sessione** nella scheda Home
2. Scegli luogo, visuale e formato del round → tocca **Avvia sessione**
3. **Tocca sulla visuale** per posizionare ogni freccia — usa il pinch-zoom e la lente di precisione per maggiore accuratezza
4. Tocca **Salva volée** quando tutte le frecce sono posizionate
5. Ripeti per ogni volée finché il round non è completo

### Qual è la differenza tra X e 10?

L'X-ring è il cerchio più interno e vale 10 punti — uguale al 10. JacArrow traccia l'X separatamente perché viene usato come spareggio nelle competizioni. Tocca il pulsante «X» quando una freccia colpisce l'X-ring in modalità score-pad.

### Come correggo una freccia mal posizionata?

1. Premi a lungo sulla freccia sulla visuale → si attiva la lente di precisione
2. Trascina la freccia nella nuova posizione → rilascia
3. OPPURE tocca la freccia per selezionarla → tocca **Elimina** per rimuoverla

In modalità score-pad: tocca il badge della freccia nello score-pad e scegli un nuovo valore.

### Cos'è la post-registrazione (l'icona 📋)?

L'icona 📋 indica sessioni inserite manualmente con lo score-pad, non registrate sulla visuale con le coordinate. Mappa degli impatti, costellazione e analisi della dispersione non sono disponibili per le sessioni post-registrate — solo i totali del punteggio.

### Come acquisto Pro?

1. Tocca una funzione bloccata con Pro (es. un tema con il badge Pro)
2. Appare il paywall con il pulsante **Acquista Pro (299 NOK)**
3. Compare la finestra di acquisto dello store → conferma (Face ID / codice su iPhone, account Google su Android)
4. Pro si attiva immediatamente — tutte le funzioni si sbloccano

**Prezzo:** 299 NOK acquisto una tantum, a vita. Nessun abbonamento, nessun addebito ricorrente.

### Come ripristino gli acquisti su un nuovo telefono?

1. Scarica JacArrow sul nuovo telefono (versione gratuita)
2. Accedi con lo stesso account usato per acquistare Pro — ID Apple su iPhone, account Google su Android
3. Apri JacArrow → **Impostazioni → Licenza → Ripristina acquisti**
4. Pro si riattiva automaticamente

Un acquisto non può passare da una piattaforma all'altra: se hai acquistato Pro su iPhone non vale su un telefono Android, e viceversa. Gli store non lo consentono. Se hai cambiato ID Apple o account Google: contatta galge.vender.0a@icloud.com e ti aiuteremo.

### Come esporto i miei dati?

**Impostazioni → Sull'app → Esporta i miei dati** → appare il menu di condivisione del telefono. Scegli AirDrop, Mail, File, Google Drive o dove vuoi inviare il file JSON.

Il JSON contiene tutte le sessioni, i round, le frecce, gli obiettivi, le configurazioni dell'arco e le impostazioni — portabilità completa ai sensi dell'art. 20 GDPR.

### Come elimino tutti i miei dati?

Disinstalla JacArrow → sia iOS sia Android rimuovono automaticamente l'intero database SQLite e tutte le impostazioni. Nessun dato residuo rimane sul dispositivo.

Se hai acquistato Pro: la ricevuta rimane presso lo store in cui hai acquistato — Apple o Google (per scopi di rimborso e supporto). La disinstallazione non influisce sulle reinstallazioni future — Pro si riattiva automaticamente tramite Ripristina acquisti.

### Quali formati di round sono supportati?

- **WA 720** (outdoor, 6 volée × 12 frecce = 72 frecce)
- **WA 18 m indoor** (10 volée × 3 frecce)
- **WA 1440** (4 distanze sequenziali)
- **Vegas Shoot** (10 volée × 3 frecce indoor 18 m)
- **AGB Portsmouth** (10 volée × 3 frecce indoor 20 yd)
- **NFAA Indoor** (12 volée × 5 frecce indoor 20 yd)
- **Allenamento libero** (nessun limite di formato)

Tutti i formati seguono la conformità ufficiale WA Book 3: regola della linea, tracciamento separato dell'X, raggi degli anelli corretti.

### Quali visuali sono supportate?

- **Visuale WA 122 cm 10-ring** (standard outdoor)
- **Visuale WA 80 cm 10-ring** (outdoor lunga distanza)
- **Visuale WA 40 cm 10-ring** (indoor, singolo spot)
- **Visuale WA 40 cm Vegas 3-spot triangolare** (gara indoor)
- **Visuale WA 40 cm Vegas 3-spot verticale** (alternativa indoor)
- **Visuale AGB Portsmouth 60 cm 10-ring** (indoor UK)
- **Visuale NFAA indoor singolo spot blu 40 cm** (USA)
- **Visuale NFAA indoor 5-spot blu 40 cm** (gara USA)

---

## Problemi tecnici

### L'app si blocca all'avvio

1. Spegni e riaccendi il telefono
2. Se persiste: disinstalla e reinstalla JacArrow (i dati di acquisto NON vengono persi — la ricevuta rimane presso lo store)
3. Inviaci una descrizione a galge.vender.0a@icloud.com — cosa stavi facendo poco prima del crash e quale telefono hai

**iPhone:** puoi trovare il log del crash da solo e allegarlo: **Impostazioni → Privacy e sicurezza → Analisi e miglioramenti → Dati di analisi** → trova il log di JacArrow → condividilo con noi. Se hai attivato «Condividi analisi app», riceviamo i log automaticamente.

**Android:** i crash ci vengono segnalati automaticamente se hai attivato «Utilizzo e diagnostica» nelle impostazioni del telefono. Non devi fare altro che descrivere cosa è successo.

### I dati di punteggio sono spariti dopo un aggiornamento

JacArrow memorizza tutto localmente in SQLite. Gli aggiornamenti migrano il database solo in avanti — i vecchi dati vengono convertiti nel nuovo formato, mai eliminati.

Se riscontri perdita di dati:
1. Verifica di essere connesso con lo stesso account di prima (ID Apple o account Google)
2. Controlla **Impostazioni → Sull'app → Numero di versione** — è aggiornato?
3. Inviaci una descrizione a galge.vender.0a@icloud.com

Abbiamo una regola ferrea che le migrazioni pubblicate sono immutabili — la perdita di dati dagli aggiornamenti non dovrebbe mai accadere. Se accade, abbiamo un bug e vogliamo saperlo.

### Il pinch-zoom non funziona sulla visuale

1. Prova con due dita, non una
2. Verifica che la riduzione del movimento non sia attiva — **iPhone: Impostazioni → Accessibilità → Movimento**, **Android: Impostazioni → Accessibilità → Rimuovi animazioni** — può limitare le gesture in alcune app
3. Chiudi l'app completamente (scorri verso l'alto dal basso, scorri JacArrow verso l'alto) e riapri

### La costellazione vibra durante il trascinamento

Era un bug in v0.28.2 e precedenti — risolto in v0.28.3. Aggiorna l'app alla versione più recente su App Store o Google Play.

---

## Feedback e richieste

### Suggerisci una nuova funzione

Invia un'email a galge.vender.0a@icloud.com con:
- **Cosa** vuoi (breve descrizione)
- **Perché** (cosa migliorerebbe nel tuo allenamento?)
- **Quanto spesso** la useresti (giornalmente / a sessione / meno frequentemente)

Leggiamo ogni singola richiesta e pubblichiamo le funzioni prioritizzate nello stream «Novità» dell'app.

### Segnala un bug

Invia un'email a galge.vender.0a@icloud.com con:
- **Cosa è andato storto** (più dettagliato possibile)
- **Cosa ti aspettavi che succedesse**
- **Passo per passo** per riprodurlo
- **Versione del sistema operativo e modello di telefono** (iPhone: Impostazioni → Generali → Info · Android: Impostazioni → Info sul telefono)
- **Versione di JacArrow** (Impostazioni → Sull'app)
- Screenshot se rilevante

### Generale
Rispondiamo a tutte le richieste entro 3 giorni lavorativi. I problemi urgenti (crash che ti impediscono di tirare) hanno priorità più alta.

---

## GDPR e privacy

Per l'informativa sulla privacy completa: [Privacy](https://mjacobsen71.github.io/jacarrow-legal/privacy-it)

Per esportare i tuoi dati, eliminare una sessione o esercitare altri diritti GDPR: vedi l'Informativa sulla privacy.

Reclami sulla privacy: contattaci **prima** a galge.vender.0a@icloud.com. Se non riusciamo a risolvere la questione, puoi presentare reclamo alla tua autorità nazionale di protezione dei dati. Per l'Italia: [Garante per la protezione dei dati personali](https://www.garanteprivacy.it/).

---

## Su JacArrow

**Sviluppatore:** Morten Jacobsen, Norvegia
**Sito web:** [mjacobsen71.github.io/jacarrow-legal](https://mjacobsen71.github.io/jacarrow-legal)
**Informativa sulla privacy:** [Privacy](https://mjacobsen71.github.io/jacarrow-legal/privacy-it)
**Licenze (open source):** vedi Impostazioni → Sull'app → Licenze nell'app

JacArrow è un progetto di un singolo sviluppatore, costruito per arcieri di ogni livello — dalla prima freccia alla centesima competizione. Il punteggio conforme al WA Book 3 è lì dal primo giorno, pronto quando lo vuoi. Costruito con React Native + Expo + TypeScript + SQLite. Niente backend, niente cloud, niente tracciamento.

Grazie per aver usato l'app. 🏹
