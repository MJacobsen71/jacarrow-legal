# Privacybeleid — JacArrow

**Laatst bijgewerkt:** 2026-08-22
**Verwerkingsverantwoordelijke:** Morten Jacobsen, Noorwegen
**Contact:** galge.vender.0a@icloud.com

---

## Korte versie

JacArrow slaat **al je data lokaal op je apparaat op**. We hebben geen
servers die je schoten, sessies of doelen ontvangen. Wanneer je
de app verwijdert, zijn alle data weg.

De enige derde partijen die informatie ontvangen, zijn:
- **Apple** (als je de app op iPhone gebruikt) — verwerkt App Store-aankopen
- **Google** (als je de app op Android gebruikt) — verwerkt Google Play-aankopen
- **RevenueCat** (na je Pro-aankoop) — verifieert je aankoop
- **Sentry** (alleen als je crashrapporten inschakelt) — ontvangt anonieme crashgegevens om ons te helpen bugs te verhelpen

Welke van de twee — Apple of Google — betrokken is, hangt af van de store waar je
de app hebt gedownload. Geen van beide is betrokken bij je schietdata zelf.

Je hebt alle AVG-rechten op inzage, verwijdering en dataportabiliteit.

---

## Wat we opslaan

### Op je apparaat (lokaal, verlaat de telefoon nooit)
- **Schietdata:** sessies, rondes, pijlplaatsingen, scores, tags, doelen, bogen en pijlsets
- **Instellingen:** gekozen taal, thema, schiethand, wedstrijdklasse, meldingsopties
- **App-geschiedenis:** coach-mark-status (welke tips je hebt gezien), tutorial-voltooid-vlaggen

Al deze data worden opgeslagen in een SQLite-database en AsyncStorage op je
telefoon. Noch JacArrow noch een derde partij heeft toegang tot deze data. Er is
geen gebruikersaccount, geen cloudopslag en geen synchronisatie tussen
apparaten — je data blijft op het apparaat waarop je die hebt vastgelegd.

### Meldingen (lokaal op het apparaat ingepland)
JacArrow kan je meldingen sturen: dat je een persoonlijk record hebt gezet, dat
je proefperiode bijna afloopt, of herinneringen over je doelen.

Die worden allemaal **lokaal op je apparaat ingepland** en berekend uit data die
het apparaat nooit verlaat. We hebben geen server die meldingen verstuurt, en we
ontvangen nooit een meldingstoken, een bezorgbevestiging of enige informatie over
wat je met een melding hebt gedaan. De bezorging zelf wordt verzorgd door het
besturingssysteem van je telefoon (iOS of Android), net als bij een wekker die je
zelf hebt gezet.

Je kunt meldingen op elk moment uitschakelen — zowel in JacArrow via
**Instellingen → Meldingen** als in de instellingen van je telefoon.

---

## Derde partijen

### Apple App Store (op iPhone)
Heb je JacArrow uit de App Store gedownload, dan worden alle in-app-aankopen
afgehandeld door Apple. We ontvangen nooit kaartgegevens, adressen of andere
betalingsgegevens. Apples
[privacybeleid](https://www.apple.com/nl/legal/privacy/) is van toepassing op het
aankoopproces.

### Google Play (op Android)
Heb je JacArrow uit Google Play gedownload, dan worden alle in-app-aankopen
afgehandeld door Google via Google Play Billing. We ontvangen nooit kaartgegevens,
adressen of andere betalingsgegevens — we horen alleen dat een aankoop is
voltooid en geldig is. Het
[privacybeleid van Google](https://policies.google.com/privacy?hl=nl) is van
toepassing op het aankoopproces.

Merk op dat Google Play, anders dan de App Store, een in-app-aankoop **niet**
deelt met een gezinsgroep. Dat is een verschil tussen de stores, niet iets wat
wij kunnen bepalen.

### RevenueCat (alleen na Pro-aankoop)
Wanneer je JacArrow Pro koopt, registreert RevenueCat je bonnetje en een
anonieme `appUserId` (UUID gegenereerd op je apparaat). Dit is nodig om
de app je aankoop te laten verifiëren bij later gebruik en bij «Aankopen
herstellen». Het bonnetje komt van de App Store of Google Play, afhankelijk van
waar je hebt gekocht. RevenueCats
[privacybeleid](https://www.revenuecat.com/privacy) is van toepassing. We sturen nooit
je naam, e-mail of andere persoonsgegevens.

### Analyse- en crashgegevens van het besturingssysteem
Zowel Apple als Google kunnen ontwikkelaars anonieme, geaggregeerde cijfers over
gebruik en crashes sturen — maar alleen als **jij** dat hebt aangezet in de
instellingen van je telefoon. Dat is een functie van de store, niet van ons: wij
zien alleen totalen, nooit iets dat naar jou te herleiden is. We gebruiken het
voor bugfixes en prestatie-optimalisatie.

- **iPhone:** geregeld via «App-analyse delen». Uitschakelen via
  **Instellingen → Privacy en beveiliging → Analyse en verbeteringen**.
- **Android:** geregeld via «Gebruik en diagnostische gegevens». Uitschakelen via
  **Instellingen → Google → Gebruik en diagnostische gegevens** (de precieze naam
  verschilt licht per fabrikant).

### Sentry (alleen als je crashrapporten hebt ingeschakeld)
Sentry is een foutmonitoringdienst die ons helpt bugs in JacArrow te identificeren
en te verhelpen. Sentry ontvangt alleen gegevens als je daar **uitdrukkelijk
toestemming** voor hebt gegeven via **Instellingen → Privacy → Crashrapporten**
(de schakelaar staat standaard UIT).

Wanneer ingeschakeld wordt het volgende naar Sentry's EU-servers (Duitsland) gestuurd:
- Crash-stack traces (bestandsnamen, regelnummers, exception-typen)
- Apparaatmodel en versie van het besturingssysteem (iOS of Android)
- App-versie en build-nummer

We sturen **niet**:
- Persoonlijke informatie (geen naam, geen e-mail, geen aan identiteit gekoppelde gebruikers-ID)
- Performance traces of transacties (`tracesSampleRate: 0`)
- IP-adressen (`sendDefaultPii: false`)

Je kunt crashrapporten op elk moment uitschakelen via dezelfde schakelaar. Wanneer
uitgeschakeld wordt Sentry **niet geïnitialiseerd** en worden er geen netwerkverzoeken gedaan.
Het [privacybeleid van Sentry](https://sentry.io/privacy/) is van toepassing op ontvangen gegevens.

---

## Wat we NIET verzamelen

- Geen gebruikersaccount, e-mailadres of wachtwoord
- Geen cloudopslag, geen back-up naar onze servers, geen synchronisatie tussen apparaten
- Geen GPS- of locatiegegevens
- Geen toegang tot contacten, agenda, camera of microfoon
- Geen trackers van derden (Firebase Analytics, Google Analytics, Facebook Pixel enz.)
- Geen advertentie-identificatoren (IDFA op iOS, advertentie-ID op Android)
- Geen video-tracking of device fingerprinting

---

## Jouw rechten (AVG)

Je hebt de volgende rechten onder de Algemene Verordening Gegevensbescherming:

**Recht op inzage (Art. 15):** Al je data wordt lokaal op je apparaat opgeslagen.
Je hebt volledige inzage via:
- Instellingen → Mijn sessies (alle historische rondes)
- Instellingen → Mijn doelen (alle actieve en gearchiveerde doelen)
- Instellingen → Bogen / Pijlsets / Schietbanen (uitrustingsbeheer)

**Recht op dataportabiliteit (Art. 20):** Gebruik
**Instellingen → Mijn data exporteren** om al je data als JSON-bestand
te downloaden. Het bestand kan via het deelvenster van je telefoon gedeeld worden
naar e-mail, AirDrop, Bestanden, Google Drive enz. Dit is je complete
schietgeschiedenis in een standaardformaat.

**Recht op wissen (Art. 17):**
- *Individuele sessie verwijderen:* veeg de sessie op het startscherm → Verwijderen
- *Alle data verwijderen:* deïnstalleer JacArrow — zowel iOS als Android
  verwijderen automatisch de hele SQLite-database en AsyncStorage. Het bonnetje
  van een Pro-aankoop wordt bewaard door de store waar je hebt gekocht (Apple of
  Google) en door RevenueCat voor terugbetaling en support.

**Recht op beperking en bezwaar (Art. 18–21):** JacArrow neemt
geen geautomatiseerde beslissingen over jou. De Smart Insights-engine analyseert alleen
je eigen trainingsdata lokaal op je apparaat en presenteert
observaties — hij neemt geen beslissingen namens jou.

**Recht om toestemming in te trekken (Art. 7):** De analysetoestemming voor Apple
en Google wordt beheerd in de instellingen van je telefoon (zie «Analyse- en
crashgegevens van het besturingssysteem» hierboven). Crashrapportage naar Sentry
schakel je uit in JacArrow via **Instellingen → Privacy**. RevenueCat-data wordt
verwijderd wanneer je de Apple ID of het Google-account verwijdert waarmee de
aankoop is gedaan.

---

## Wijzigingen

We werken dit beleid bij wanneer er belangrijke wijzigingen plaatsvinden in hoe we
data verwerken. Wijzigingen worden gecommuniceerd via:
1. De datum «Laatst bijgewerkt» bovenaan deze pagina
2. In-app-banner bij de eerste start na een update als de wijziging substantieel is
   (bijv. nieuwe derde partijen, nieuwe dataverzameling)

---

## Klachten

Als je vindt dat we je persoonsgegevens in strijd met de AVG verwerken,
heb je het recht om een klacht in te dienen bij je nationale gegevensbeschermingsautoriteit:

- **Nederland:** [Autoriteit Persoonsgegevens](https://autoriteitpersoonsgegevens.nl/)
- **EU/EER:** vind je autoriteit op
  [edpb.europa.eu](https://www.edpb.europa.eu/about-edpb/about-edpb/members_en)

We moedigen je aan eerst contact met ons op te nemen via galge.vender.0a@icloud.com — we nemen
alle privacyvragen serieus.
