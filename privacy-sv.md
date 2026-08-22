# Integritetspolicy — JacArrow

**Senast uppdaterad:** 2026-08-22
**Personuppgiftsansvarig:** Morten Jacobsen, Norge
**Kontakt:** galge.vender.0a@icloud.com

---

## Kort version

JacArrow lagrar **all din data lokalt på din enhet**. Vi har inga
servrar som tar emot dina skott, pass eller mål. När du avinstallerar
appen försvinner all data.

De enda tredje parter som tar emot information är:
- **Apple** (om du använder appen på iPhone) — hanterar App Store-köp
- **Google** (om du använder appen på Android) — hanterar Google Play-köp
- **RevenueCat** (efter att du köpt Pro) — verifierar ditt köp
- **Sentry** (endast om du aktiverar kraschrapporter) — tar emot anonyma kraschdata för att hjälpa oss åtgärda buggar

Vilken av Apple och Google som är inblandad beror på vilken butik du laddade
ner appen från. Ingen av dem är inblandad i själva skyttedatan.

Du har fullständiga GDPR-rättigheter till tillgång, radering och dataportabilitet.

---

## Vad vi lagrar

### På din enhet (lokalt, lämnar aldrig telefonen)
- **Skyttedata:** pass, omgångar, pilplaceringar, poäng, taggar, mål, bågar och pilset
- **Inställningar:** valt språk, tema, skytteshand, tävlingsklass, notisinställningar
- **App-historik:** coach-mark-status (vilka tips du har sett), tutorial-färdigflaggor

All denna data lagras i en SQLite-databas och AsyncStorage på din telefon.
Varken JacArrow eller någon tredje part har tillgång till denna data. Det finns
inget användarkonto, ingen molnlagring och ingen synkronisering mellan enheter —
din data stannar på den enhet du registrerade den på.

### Notiser (schemaläggs lokalt på enheten)
JacArrow kan skicka dig notiser: att du satt personligt rekord, att provperioden
närmar sig sitt slut, eller påminnelser om dina mål.

Alla dessa **schemaläggs lokalt på din enhet** och beräknas från data som aldrig
lämnar den. Vi har ingen server som skickar notiser, och vi tar aldrig emot
någon notis-token, någon leveransbekräftelse eller någon uppgift om vad du
gjorde med en notis. Själva leveransen hanteras av telefonens operativsystem
(iOS eller Android), precis som ett alarm du själv har ställt.

Du kan stänga av notiser när som helst — både i JacArrow under
**Inställningar → Notiser** och i telefonens egna inställningar.

---

## Tredje parter

### Apple App Store (på iPhone)
Har du laddat ner JacArrow från App Store hanteras alla köp i appen av Apple.
Vi tar aldrig emot kortuppgifter, adresser eller andra betalningsuppgifter.
Apples [integritetspolicy](https://www.apple.com/se/legal/privacy/) gäller för
köpflödet.

### Google Play (på Android)
Har du laddat ner JacArrow från Google Play hanteras alla köp i appen av Google
via Google Play Billing. Vi tar aldrig emot kortuppgifter, adresser eller andra
betalningsuppgifter — vi får bara veta att ett köp är genomfört och giltigt.
Googles [integritetspolicy](https://policies.google.com/privacy?hl=sv) gäller
för köpflödet.

Observera att Google Play, till skillnad från App Store, **inte** delar ett köp
i appen vidare till en familjegrupp. Det är en skillnad mellan butikerna, inte
något vi kan styra.

### RevenueCat (endast efter Pro-köp)
När du köper JacArrow Pro registrerar RevenueCat ditt kvitto och ett
anonymt `appUserId` (UUID genererat på din enhet). Detta krävs för
att appen ska kunna verifiera ditt köp vid senare användning och vid «Återställ
köp». Kvittot kommer från App Store eller Google Play beroende på var du köpte.
RevenueCats
[integritetspolicy](https://www.revenuecat.com/privacy) gäller. Vi skickar aldrig
ditt namn, e-post eller andra personuppgifter.

### Analys- och kraschdata från operativsystemet
Både Apple och Google kan skicka utvecklare anonyma, aggregerade siffror om
användning och krascher — men bara om **du** har slagit på det i telefonens egna
inställningar. Det är butikens funktion, inte vår: vi ser bara summor, aldrig
något som kan spåras till dig. Vi använder det för felrättning och
prestandaoptimering.

- **iPhone:** styrs av «Dela app-analys». Stäng av via
  **Inställningar → Integritet och säkerhet → Analys och förbättringar**.
- **Android:** styrs av «Användning och diagnostik». Stäng av via
  **Inställningar → Google → Användning och diagnostik** (namnet varierar något
  mellan tillverkare).

### Sentry (endast om du har aktiverat kraschrapporter)
Sentry är en felövervakningstjänst som hjälper oss att identifiera och åtgärda
buggar i JacArrow. Sentry tar endast emot data om du har gett
**uttryckligt samtycke** via **Inställningar → Integritet → Kraschrapporter**
(reglaget är AV som standard).

När det är aktiverat skickas följande till Sentrys EU-servrar (Tyskland):
- Krasch-stackspår (filnamn, radnummer, exception-typer)
- Enhetsmodell och operativsystemversion (iOS eller Android)
- App-version och build-nummer

Vi skickar **inte**:
- Personlig information (inget namn, ingen e-post, inget användar-ID kopplat till identitet)
- Prestandaspår eller transaktioner (`tracesSampleRate: 0`)
- IP-adresser (`sendDefaultPii: false`)

Du kan inaktivera kraschrapporter när som helst via samma reglage. När det är
inaktiverat **initieras inte** Sentry och inga nätverksförfrågningar görs.
Sentrys [integritetspolicy](https://sentry.io/privacy/) gäller för mottagen data.

---

## Vad vi INTE samlar in

- Inget användarkonto, ingen e-postadress, inget lösenord
- Ingen molnlagring, ingen backup till våra servrar, ingen synkronisering mellan enheter
- Inga GPS- eller positionsdata
- Ingen åtkomst till kontakter, kalender, kamera eller mikrofon
- Inga tredjepartsspårare (Firebase Analytics, Google Analytics, Facebook Pixel m.fl.)
- Inga annonsidentifierare (IDFA på iOS, annons-ID på Android)
- Ingen videospårning eller enhetsfingeravtryck

---

## Dina rättigheter (GDPR)

Du har följande rättigheter enligt dataskyddsförordningen:

**Rätt till tillgång (Art. 15):** All din data lagras lokalt på din enhet.
Du har full insyn via:
- Inställningar → Mina pass (alla historiska omgångar)
- Inställningar → Mina mål (alla aktiva och arkiverade mål)
- Inställningar → Bågar / Pilset / Banor (utrustningshantering)

**Rätt till dataportabilitet (Art. 20):** Använd
**Inställningar → Exportera mina data** för att ladda ner all din data som
JSON-fil. Filen kan delas via telefonens delningsmeny till e-post, AirDrop,
Filer, Google Drive m.fl. Detta är din kompletta skyttehistorik i ett
standardformat.

**Rätt till radering (Art. 17):**
- *Ta bort enskilt pass:* svep passet på startskärmen → Ta bort
- *Ta bort all data:* avinstallera JacArrow — både iOS och Android tar
  automatiskt bort hela SQLite-databasen och AsyncStorage. Kvittot för ett
  Pro-köp behålls hos den butik du köpte i (Apple eller Google) och hos
  RevenueCat för återbetalnings- och supportändamål.

**Rätt till begränsning och invändning (Art. 18–21):** JacArrow fattar
inga automatiserade beslut om dig. Smart Insights-motorn analyserar enbart
dina egna träningsdata lokalt på din enhet och presenterar
observationer — den fattar inga beslut å dina vägnar.

**Rätt att återkalla samtycke (Art. 7):** Analyssamtycket till Apple och Google
styrs i telefonens egna inställningar (se «Analys- och kraschdata från
operativsystemet» ovan). Kraschrapportering till Sentry stängs av i JacArrow
under **Inställningar → Integritet**. RevenueCat-data raderas när du raderar det
Apple-ID eller Google-konto som köpet gjordes med.

---

## Ändringar

Vi uppdaterar denna policy när väsentliga ändringar sker i hur vi behandlar
data. Ändringar kommuniceras via:
1. Datumet «Senast uppdaterad» högst upp på denna sida
2. In-app-banner vid första start efter uppdatering om ändringen är väsentlig
   (t.ex. nya tredje parter, ny datainsamling)

---

## Klagomål

Om du anser att vi behandlar dina personuppgifter i strid med GDPR har du
rätt att klaga till din nationella dataskyddsmyndighet:

- **Sverige:** [Integritetsskyddsmyndigheten (IMY)](https://www.imy.se/)
- **EU/EES:** hitta din myndighet på
  [edpb.europa.eu](https://www.edpb.europa.eu/about-edpb/about-edpb/members_en)

Vi uppmuntrar dig att kontakta oss först på galge.vender.0a@icloud.com — vi tar
alla integritetsfrågor på allvar.
