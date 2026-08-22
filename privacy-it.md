# Informativa sulla privacy — JacArrow

**Ultimo aggiornamento:** 2026-08-22
**Titolare del trattamento:** Morten Jacobsen, Norvegia
**Contatto:** galge.vender.0a@icloud.com

---

## Versione breve

JacArrow memorizza **tutti i tuoi dati localmente sul tuo dispositivo**. Non abbiamo alcun
server che riceva i tuoi tiri, le tue sessioni o i tuoi obiettivi. Quando disinstalli
l'app, tutti i dati spariscono.

Le uniche terze parti che ricevono informazioni sono:
- **Apple** (se usi l'app su iPhone) — gestisce gli acquisti su App Store
- **Google** (se usi l'app su Android) — gestisce gli acquisti su Google Play
- **RevenueCat** (dopo l'acquisto di Pro) — verifica il tuo acquisto
- **Sentry** (solo se attivi le segnalazioni di crash) — riceve dati anonimi sui crash per aiutarci a correggere i bug

Quale delle due — Apple o Google — sia coinvolta dipende dallo store da cui hai
scaricato l'app. Nessuna delle due è coinvolta nei tuoi dati di tiro.

Hai i pieni diritti GDPR di accesso, cancellazione e portabilità dei dati.

---

## Cosa memorizziamo

### Sul tuo dispositivo (in locale, non lascia mai il telefono)
- **Dati di tiro:** sessioni, round, posizionamenti delle frecce, punteggi, etichette, obiettivi, archi e set di frecce
- **Impostazioni:** lingua selezionata, tema, mano di tiro, classe di gara, opzioni di notifica
- **Cronologia dell'app:** stato dei coach-mark (suggerimenti già visualizzati), flag di tutorial completati

Tutti questi dati sono memorizzati in un database SQLite e in AsyncStorage sul
tuo telefono. Né JacArrow né alcuna terza parte ha accesso a questi dati. Non
esiste alcun account utente, alcuna archiviazione cloud e alcuna
sincronizzazione tra dispositivi — i tuoi dati restano sul dispositivo su cui
li hai registrati.

### Notifiche (pianificate localmente sul dispositivo)
JacArrow può inviarti notifiche: che hai stabilito un record personale, che il
periodo di prova sta per terminare, oppure promemoria sui tuoi obiettivi.

Tutte vengono **pianificate localmente sul tuo dispositivo** e calcolate da dati
che non lo lasciano mai. Non abbiamo alcun server che invii notifiche e non
riceviamo mai un token di notifica, una conferma di consegna né alcuna
informazione su cosa hai fatto con una notifica. La consegna in sé è gestita dal
sistema operativo del telefono (iOS o Android), esattamente come una sveglia che
hai impostato tu.

Puoi disattivare le notifiche in qualsiasi momento — sia in JacArrow tramite
**Impostazioni → Notifiche**, sia nelle impostazioni del telefono.

---

## Terze parti

### Apple App Store (su iPhone)
Se hai scaricato JacArrow dall'App Store, tutti gli acquisti in-app sono gestiti
da Apple. Non riceviamo mai informazioni sulla carta, indirizzi o altri dettagli
di pagamento. La
[politica sulla privacy di Apple](https://www.apple.com/it/legal/privacy/) si applica al
processo di acquisto.

### Google Play (su Android)
Se hai scaricato JacArrow da Google Play, tutti gli acquisti in-app sono gestiti
da Google tramite Google Play Billing. Non riceviamo mai informazioni sulla
carta, indirizzi o altri dettagli di pagamento — ci viene comunicato solo che un
acquisto è stato completato ed è valido. L'
[informativa sulla privacy di Google](https://policies.google.com/privacy?hl=it)
si applica al processo di acquisto.

Nota che Google Play, a differenza dell'App Store, **non** condivide un acquisto
in-app con un gruppo famiglia. È una differenza tra gli store, non qualcosa che
possiamo controllare.

### RevenueCat (solo dopo l'acquisto di Pro)
Quando acquisti JacArrow Pro, RevenueCat registra la tua ricevuta e un
`appUserId` anonimo (UUID generato sul tuo dispositivo). Ciò è necessario
affinché l'app possa verificare il tuo acquisto in utilizzi successivi e durante il
«Ripristina acquisti». La ricevuta proviene dall'App Store o da Google Play, a
seconda di dove hai acquistato. La
[politica sulla privacy di RevenueCat](https://www.revenuecat.com/privacy) si applica. Non inviamo mai
il tuo nome, la tua email o altri dati personali.

### Analisi e dati di crash del sistema operativo
Sia Apple sia Google possono inviare agli sviluppatori numeri anonimi e
aggregati su utilizzo e crash — ma solo se **tu** l'hai attivato nelle
impostazioni del telefono. È una funzione dello store, non nostra: vediamo solo
totali, mai qualcosa che possa risalire a te. La usiamo per la correzione dei
bug e l'ottimizzazione delle prestazioni.

- **iPhone:** controllato da «Condividi analisi app». Disattiva tramite
  **Impostazioni → Privacy e sicurezza → Analisi e miglioramenti**.
- **Android:** controllato da «Utilizzo e diagnostica». Disattiva tramite
  **Impostazioni → Google → Utilizzo e diagnostica** (il nome esatto varia
  leggermente tra i produttori).

### Sentry (solo se hai abilitato le segnalazioni di crash)
Sentry è un servizio di monitoraggio degli errori che ci aiuta a identificare e
correggere i bug in JacArrow. Sentry riceve dati solo se hai dato
**esplicito consenso** tramite **Impostazioni → Privacy → Segnalazioni di crash**
(l'interruttore è disattivato per impostazione predefinita).

Quando attivato, vengono inviati ai server europei di Sentry (Germania):
- Stack trace dei crash (nomi file, numeri di riga, tipi di eccezione)
- Modello del dispositivo e versione del sistema operativo (iOS o Android)
- Versione dell'app e numero di build

**Non** inviamo:
- Informazioni personali (nessun nome, nessuna email, nessun ID utente collegato all'identità)
- Trace di performance o transazioni (`tracesSampleRate: 0`)
- Indirizzi IP (`sendDefaultPii: false`)

Puoi disattivare le segnalazioni di crash in qualsiasi momento tramite lo stesso interruttore. Quando
disattivato, Sentry **non viene inizializzato** e non vengono effettuate richieste di rete.
L'[informativa sulla privacy di Sentry](https://sentry.io/privacy/) si applica ai dati ricevuti.

---

## Cosa NON raccogliamo

- Nessun account utente, indirizzo email o password
- Nessuna archiviazione cloud, nessun backup sui nostri server, nessuna sincronizzazione tra dispositivi
- Nessun dato GPS o di posizione
- Nessun accesso a contatti, calendario, fotocamera o microfono
- Nessun tracker di terze parti (Firebase Analytics, Google Analytics, Facebook Pixel, ecc.)
- Nessun identificatore pubblicitario (IDFA su iOS, ID pubblicità su Android)
- Nessun video-tracking né fingerprinting del dispositivo

---

## I tuoi diritti (GDPR)

Hai i seguenti diritti ai sensi del Regolamento generale sulla protezione dei dati:

**Diritto di accesso (Art. 15):** Tutti i tuoi dati sono memorizzati localmente sul tuo dispositivo.
Hai piena visibilità tramite:
- Impostazioni → Le mie sessioni (tutti i round storici)
- Impostazioni → I miei obiettivi (tutti gli obiettivi attivi e archiviati)
- Impostazioni → Archi / Set di frecce / Luoghi (gestione attrezzatura)

**Diritto alla portabilità dei dati (Art. 20):** Usa
**Impostazioni → Esporta i miei dati** per scaricare tutti i tuoi dati come file JSON. Il
file può essere condiviso tramite il menu di condivisione del telefono a email,
AirDrop, File, Google Drive, ecc. Questa è la tua cronologia di tiro completa in
un formato standard.

**Diritto alla cancellazione (Art. 17):**
- *Eliminare una singola sessione:* fai scorrere la sessione sulla schermata Home → Elimina
- *Eliminare tutti i dati:* disinstalla JacArrow — sia iOS sia Android eliminano
  automaticamente l'intero database SQLite e AsyncStorage. La ricevuta di un
  acquisto Pro viene conservata dallo store in cui hai acquistato (Apple o
  Google) e da RevenueCat per scopi di rimborso e supporto.

**Diritto di limitazione e opposizione (Art. 18–21):** JacArrow non prende
alcuna decisione automatizzata su di te. Il motore Smart Insights analizza solo
i tuoi dati di allenamento localmente sul tuo dispositivo e presenta
osservazioni — non prende decisioni per tuo conto.

**Diritto di revocare il consenso (Art. 7):** Il consenso alle analisi di Apple
e Google è controllato nelle impostazioni del telefono (vedi «Analisi e dati di
crash del sistema operativo» sopra). Le segnalazioni di crash a Sentry si
disattivano in JacArrow tramite **Impostazioni → Privacy**. I dati RevenueCat
vengono eliminati quando elimini l'ID Apple o l'account Google con cui è stato
effettuato l'acquisto.

---

## Modifiche

Aggiorneremo questa informativa in caso di modifiche significative nelle modalità di
trattamento dei dati. Le modifiche sono comunicate tramite:
1. Data «Ultimo aggiornamento» in cima a questa pagina
2. Banner in-app al primo avvio dopo l'aggiornamento se la modifica è sostanziale
   (es. nuove terze parti, nuova raccolta di dati)

---

## Reclami

Se ritieni che stiamo trattando i tuoi dati personali in violazione del GDPR,
hai il diritto di presentare un reclamo alla tua autorità nazionale di protezione dei dati:

- **Italia:** [Garante per la protezione dei dati personali](https://www.garanteprivacy.it/)
- **UE/SEE:** trova la tua autorità su
  [edpb.europa.eu](https://www.edpb.europa.eu/about-edpb/about-edpb/members_en)

Ti invitiamo a contattarci prima a galge.vender.0a@icloud.com — prendiamo
tutte le richieste sulla privacy seriamente.
