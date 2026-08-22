# Datenschutzerklärung — JacArrow

**Zuletzt aktualisiert:** 2026-08-22
**Verantwortlicher:** Morten Jacobsen, Norwegen
**Kontakt:** galge.vender.0a@icloud.com

---

## Kurzfassung

JacArrow speichert **alle deine Daten lokal auf deinem Gerät**. Wir haben keine
Server, die deine Schüsse, Trainingseinheiten oder Ziele empfangen. Wenn du
die App deinstallierst, sind alle Daten weg.

Die einzigen Dritten, die Informationen erhalten, sind:
- **Apple** (wenn du die App auf dem iPhone nutzt) — wickelt App-Store-Käufe ab
- **Google** (wenn du die App auf Android nutzt) — wickelt Google-Play-Käufe ab
- **RevenueCat** (nachdem du Pro gekauft hast) — überprüft deinen Kauf
- **Sentry** (nur wenn du Absturzberichten zustimmst) — erhält anonyme Absturzdaten, damit wir Fehler beheben können

Welcher der beiden — Apple oder Google — beteiligt ist, hängt davon ab, aus
welchem Store du die App geladen hast. Keiner von beiden ist an deinen
Schießdaten selbst beteiligt.

Du hast nach DSGVO volle Rechte auf Auskunft, Löschung und Datenübertragbarkeit.

---

## Was wir speichern

### Auf deinem Gerät (lokal, verlässt niemals das Smartphone)
- **Schießdaten:** Trainingseinheiten, Runden, Pfeilplatzierungen, Punktzahlen, Tags, Ziele, Bögen und Pfeilsätze
- **Einstellungen:** ausgewählte Sprache, Theme, Schießhand, Wettkampfklasse, Benachrichtigungsoptionen
- **App-Verlauf:** Coach-Mark-Status (welche Tipps du gesehen hast), Tutorial-Abschluss-Flags

Alle diese Daten werden in einer SQLite-Datenbank und in AsyncStorage auf deinem
Smartphone gespeichert. Weder JacArrow noch ein Dritter hat Zugriff auf diese
Daten. Es gibt kein Benutzerkonto, keinen Cloud-Speicher und keine
Synchronisierung zwischen Geräten — deine Daten bleiben auf dem Gerät, auf dem
du sie erfasst hast.

### Benachrichtigungen (lokal auf dem Gerät geplant)
JacArrow kann dir Benachrichtigungen senden: dass du einen persönlichen Rekord
aufgestellt hast, dass dein Testzeitraum zu Ende geht, oder Erinnerungen an
deine Ziele.

Alle diese werden **lokal auf deinem Gerät geplant** und aus Daten berechnet,
die es niemals verlassen. Wir haben keinen Server, der Benachrichtigungen
sendet, und wir erhalten niemals ein Benachrichtigungs-Token, eine
Zustellbestätigung oder eine Angabe darüber, was du mit einer Benachrichtigung
gemacht hast. Die Zustellung selbst übernimmt das Betriebssystem deines
Smartphones (iOS oder Android) — genauso wie bei einem Wecker, den du selbst
gestellt hast.

Du kannst Benachrichtigungen jederzeit deaktivieren — sowohl in JacArrow unter
**Einstellungen → Benachrichtigungen** als auch in den Einstellungen deines
Smartphones.

---

## Dritte

### Apple App Store (auf dem iPhone)
Hast du JacArrow aus dem App Store geladen, werden alle In-App-Käufe von Apple
abgewickelt. Wir erhalten niemals Karteninformationen, Adressen oder andere
Zahlungsdetails. Apples
[Datenschutzrichtlinie](https://www.apple.com/legal/privacy/) gilt für
den Kaufvorgang.

### Google Play (auf Android)
Hast du JacArrow aus Google Play geladen, werden alle In-App-Käufe von Google
über Google Play Billing abgewickelt. Wir erhalten niemals Karteninformationen,
Adressen oder andere Zahlungsdetails — wir erfahren nur, dass ein Kauf
abgeschlossen und gültig ist. Googles
[Datenschutzerklärung](https://policies.google.com/privacy?hl=de) gilt für den
Kaufvorgang.

Beachte, dass Google Play — anders als der App Store — einen In-App-Kauf
**nicht** mit einer Familiengruppe teilt. Das ist ein Unterschied zwischen den
Stores und nicht von uns steuerbar.

### RevenueCat (nur nach Pro-Kauf)
Wenn du JacArrow Pro kaufst, zeichnet RevenueCat deine Quittung und eine
anonyme `appUserId` (eine auf deinem Gerät generierte UUID) auf. Dies ist notwendig,
damit die App deinen Kauf bei späterer Nutzung und beim «Käufe
wiederherstellen» überprüfen kann. Die Quittung stammt aus dem App Store oder
von Google Play, je nachdem, wo du gekauft hast. RevenueCats
[Datenschutzrichtlinie](https://www.revenuecat.com/privacy) gilt. Wir senden niemals
deinen Namen, deine E-Mail oder andere personenbezogene Daten.

### Analyse- und Absturzdaten des Betriebssystems
Sowohl Apple als auch Google können Entwicklern anonyme, aggregierte Zahlen
über Nutzung und Abstürze senden — aber nur, wenn **du** das in den
Einstellungen deines Smartphones aktiviert hast. Das ist eine Funktion des
Stores, nicht von uns: wir sehen nur Summen, niemals etwas, das sich zu dir
zurückverfolgen lässt. Wir nutzen es für Fehlerbehebungen und
Performance-Optimierung.

- **iPhone:** gesteuert über «App-Analyse teilen». Deaktivieren über
  **Einstellungen → Datenschutz & Sicherheit → Analyse & Verbesserungen**.
- **Android:** gesteuert über «Nutzung & Diagnose». Deaktivieren über
  **Einstellungen → Google → Nutzung & Diagnose** (die genaue Bezeichnung
  variiert je nach Hersteller leicht).

### Sentry (nur wenn du Absturzberichte aktiviert hast)
Sentry ist ein Fehlerüberwachungsdienst, der uns hilft, Bugs in JacArrow zu
identifizieren und zu beheben. Sentry erhält nur dann Daten, wenn du dem
**ausdrücklich zugestimmt** hast über **Einstellungen → Datenschutz → Absturzberichte**
(der Schalter ist standardmäßig AUS).

Nach Opt-in wird Folgendes an Sentrys EU-Server (Deutschland) gesendet:
- Absturz-Stack-Traces (Dateinamen, Zeilennummern, Exception-Typen)
- Gerätemodell und Betriebssystemversion (iOS oder Android)
- App-Version und Build-Nummer

Wir senden **nicht**:
- Persönliche Informationen (kein Name, keine E-Mail, keine identitätsverknüpfte Nutzer-ID)
- Performance-Traces oder Transaktionen (`tracesSampleRate: 0`)
- IP-Adressen (`sendDefaultPii: false`)

Du kannst Absturzberichte jederzeit über denselben Schalter deaktivieren. Wenn
deaktiviert, wird Sentry **nicht initialisiert** und es werden keine Netzwerkanfragen gestellt.
Sentrys [Datenschutzrichtlinie](https://sentry.io/privacy/) gilt für empfangene Daten.

---

## Was wir NICHT sammeln

- Kein Benutzerkonto, keine E-Mail-Adresse, kein Passwort
- Kein Cloud-Speicher, kein Backup auf unseren Servern, keine Synchronisierung zwischen Geräten
- Keine GPS- oder Standortdaten
- Kein Zugriff auf Kontakte, Kalender, Kamera oder Mikrofon
- Keine Tracker von Dritten (Firebase Analytics, Google Analytics, Facebook Pixel usw.)
- Keine Werbe-Identifikatoren (IDFA auf iOS, Werbe-ID auf Android)
- Kein Videotracking, kein Device-Fingerprinting

---

## Deine Rechte (DSGVO)

Du hast nach der Datenschutz-Grundverordnung folgende Rechte:

**Auskunftsrecht (Art. 15):** Alle deine Daten sind lokal auf deinem Gerät gespeichert.
Du hast volle Einsicht über:
- Einstellungen → Meine Trainingseinheiten (alle bisherigen Runden)
- Einstellungen → Meine Ziele (alle aktiven und archivierten Ziele)
- Einstellungen → Bögen / Pfeilsätze / Orte (Geräteverwaltung)

**Recht auf Datenübertragbarkeit (Art. 20):** Nutze
**Einstellungen → Meine Daten exportieren**, um alle deine Daten als JSON-Datei
herunterzuladen. Die Datei kann über das Teilen-Menü deines Smartphones an
E-Mail, AirDrop, Dateien, Google Drive usw. geteilt werden. Dies ist deine
komplette Schieß-Historie in einem Standardformat.

**Recht auf Löschung (Art. 17):**
- *Einzelne Trainingseinheit löschen:* Wische die Einheit auf dem Startbildschirm → Löschen
- *Alle Daten löschen:* Deinstalliere JacArrow — sowohl iOS als auch Android
  löschen automatisch die gesamte SQLite-Datenbank und AsyncStorage. Die
  Quittung für einen Pro-Kauf bleibt bei dem Store, in dem du gekauft hast
  (Apple oder Google), und bei RevenueCat für Erstattungs- und Support-Zwecke
  erhalten.

**Recht auf Einschränkung und Widerspruch (Art. 18–21):** JacArrow trifft
keinerlei automatisierte Entscheidungen über dich. Die Smart-Insights-Engine analysiert
nur deine eigenen Trainingsdaten lokal auf deinem Gerät und präsentiert
Beobachtungen — sie trifft keine Entscheidungen in deinem Namen.

**Recht auf Widerruf der Einwilligung (Art. 7):** Die Analyse-Einwilligung für
Apple und Google wird in den Einstellungen deines Smartphones gesteuert (siehe
«Analyse- und Absturzdaten des Betriebssystems» oben). Absturzberichte an
Sentry deaktivierst du in JacArrow unter **Einstellungen → Datenschutz**.
RevenueCat-Daten werden gelöscht, wenn du die Apple-ID oder das
Google-Konto löschst, mit dem der Kauf getätigt wurde.

---

## Änderungen

Wir aktualisieren diese Erklärung, wenn wesentliche Änderungen in der Art und Weise auftreten,
wie wir Daten verarbeiten. Änderungen werden kommuniziert über:
1. Datum «Zuletzt aktualisiert» oben auf dieser Seite
2. In-App-Banner beim ersten Start nach dem Update, wenn die Änderung wesentlich ist
   (z. B. neue Dritte, neue Datenerhebung)

---

## Beschwerden

Wenn du der Meinung bist, dass wir deine personenbezogenen Daten unter Verletzung der DSGVO
verarbeiten, hast du das Recht, dich bei deiner nationalen Datenschutzbehörde zu beschweren:

- **Deutschland:** [Bundesbeauftragte für den Datenschutz und die Informationsfreiheit (BfDI)](https://www.bfdi.bund.de/)
- **EU/EWR:** Finde deine Behörde unter
  [edpb.europa.eu](https://www.edpb.europa.eu/about-edpb/about-edpb/members_en)

Wir bitten dich, uns zuerst unter galge.vender.0a@icloud.com zu kontaktieren — wir nehmen
alle Datenschutzanfragen ernst.
