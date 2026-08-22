# Privatlivspolitik — JacArrow

**Sidst opdateret:** 2026-08-22
**Dataansvarlig:** Morten Jacobsen, Norge
**Kontakt:** galge.vender.0a@icloud.com

---

## Kort version

JacArrow gemmer **alle dine data lokalt på din enhed**. Vi har ingen
servere, der modtager dine skud, pas eller mål. Når du afinstallerer
appen, forsvinder alle data.

De eneste tredjeparter, der modtager information, er:
- **Apple** (hvis du bruger appen på iPhone) — håndterer App Store-køb
- **Google** (hvis du bruger appen på Android) — håndterer Google Play-køb
- **RevenueCat** (efter du har købt Pro) — verificerer dit køb
- **Sentry** (kun hvis du aktiverer nedbrudsrapporter) — modtager anonyme nedbrudsdata, så vi kan rette fejl

Hvilken af Apple og Google der er involveret, afhænger af hvilken butik du
hentede appen fra. Ingen af dem er involveret i selve dine skydedata.

Du har fulde GDPR-rettigheder til indsigt, sletning og dataportabilitet.

---

## Hvad vi gemmer

### På din enhed (lokalt, forlader aldrig telefonen)
- **Skydedata:** pas, runder, pilplaceringer, point, tags, mål, buer og pilset
- **Indstillinger:** valgt sprog, tema, skydehånd, konkurrenceklasse, notifikations-indstillinger
- **App-historik:** coach-mark-status (hvilke tips du har set), tutorial-fuldført-flag

Alle disse data gemmes i en SQLite-database og AsyncStorage på din telefon.
Hverken JacArrow eller nogen tredjepart har adgang til disse data. Der er ingen
brugerkonto, ingen skylagring og ingen synkronisering mellem enheder — dine data
bliver på den enhed, du registrerede dem på.

### Notifikationer (planlægges lokalt på enheden)
JacArrow kan sende dig notifikationer: at du har sat personlig rekord, at
prøveperioden nærmer sig sin afslutning, eller påmindelser om dine mål.

Alle disse **planlægges lokalt på din enhed** og beregnes ud fra data, der aldrig
forlader den. Vi har ingen server, der sender notifikationer, og vi modtager
aldrig et notifikations-token, en leveringsbekræftelse eller nogen oplysning om,
hvad du gjorde med en notifikation. Selve leveringen håndteres af telefonens
operativsystem (iOS eller Android), præcis som en alarm du selv har sat.

Du kan slå notifikationer fra når som helst — både i JacArrow under
**Indstillinger → Notifikationer** og i telefonens egne indstillinger.

---

## Tredjeparter

### Apple App Store (på iPhone)
Har du hentet JacArrow fra App Store, håndteres alle in-app-køb af Apple. Vi
modtager aldrig kortoplysninger, adresser eller andre betalingsdetaljer. Apples
[privatlivspolitik](https://www.apple.com/dk/legal/privacy/) gælder for
købsflowet.

### Google Play (på Android)
Har du hentet JacArrow fra Google Play, håndteres alle in-app-køb af Google via
Google Play Billing. Vi modtager aldrig kortoplysninger, adresser eller andre
betalingsdetaljer — vi får kun at vide, at et køb er gennemført og gyldigt.
Googles [privatlivspolitik](https://policies.google.com/privacy?hl=da) gælder
for købsflowet.

Bemærk, at Google Play — i modsætning til App Store — **ikke** deler et
in-app-køb videre til en familiegruppe. Det er en forskel mellem butikkerne,
ikke noget vi kan styre.

### RevenueCat (kun efter Pro-køb)
Når du køber JacArrow Pro, registrerer RevenueCat din kvittering og et
anonymt `appUserId` (UUID genereret på din enhed). Dette er nødvendigt for,
at appen kan verificere dit køb ved senere brug og ved «Gendan
køb». Kvitteringen kommer fra App Store eller Google Play, afhængigt af hvor du
købte. RevenueCats
[privatlivspolitik](https://www.revenuecat.com/privacy) gælder. Vi sender aldrig
dit navn, e-mail eller andre personoplysninger.

### Analyse- og nedbrudsdata fra operativsystemet
Både Apple og Google kan sende udviklere anonyme, aggregerede tal om brug og
nedbrud — men kun hvis **du** har slået det til i telefonens egne indstillinger.
Det er butikkens funktion, ikke vores: vi ser kun summer, aldrig noget der kan
spores tilbage til dig. Vi bruger det til fejlrettelse og ydeevneoptimering.

- **iPhone:** styres af «Del app-analyse». Slå fra via
  **Indstillinger → Anonymitet og sikkerhed → Analyse og forbedringer**.
- **Android:** styres af «Brug og diagnosticering». Slå fra via
  **Indstillinger → Google → Brug og diagnosticering** (navnet varierer en smule
  mellem producenter).

### Sentry (kun hvis du har aktiveret nedbrudsrapporter)
Sentry er en fejlovervågningstjeneste, der hjælper os med at identificere og rette
fejl i JacArrow. Sentry modtager kun data, hvis du har givet
**udtrykkeligt samtykke** via **Indstillinger → Privatliv → Nedbrudsrapporter**
(kontakten er som standard SLÅET FRA).

Når den er slået til, sendes følgende til Sentrys EU-servere (Tyskland):
- Nedbruds-stack traces (filnavne, linjenumre, exception-typer)
- Enhedsmodel og operativsystemversion (iOS eller Android)
- App-version og build-nummer

Vi sender **ikke**:
- Personlige oplysninger (intet navn, ingen e-mail, intet bruger-ID knyttet til identitet)
- Ydelses-traces eller transaktioner (`tracesSampleRate: 0`)
- IP-adresser (`sendDefaultPii: false`)

Du kan deaktivere nedbrudsrapporter når som helst via den samme kontakt. Når den er
deaktiveret, **initialiseres Sentry ikke**, og der foretages ingen netværksanmodninger.
Sentrys [privatlivspolitik](https://sentry.io/privacy/) gælder for modtagne data.

---

## Det vi IKKE indsamler

- Ingen brugerkonto, e-mailadresse eller adgangskode
- Ingen skylagring, ingen backup til vores servere, ingen synkronisering mellem enheder
- Ingen GPS- eller positionsdata
- Ingen adgang til kontakter, kalender, kamera eller mikrofon
- Ingen tredjeparts-trackere (Firebase Analytics, Google Analytics, Facebook Pixel osv.)
- Ingen reklame-identifikatorer (IDFA på iOS, annonce-id på Android)
- Ingen video-tracking eller enheds-fingeraftryk

---

## Dine rettigheder (GDPR)

Du har følgende rettigheder under databeskyttelsesforordningen:

**Ret til indsigt (Art. 15):** Alle dine data er gemt lokalt på din enhed.
Du har fuld indsigt via:
- Indstillinger → Mine pas (alle historiske runder)
- Indstillinger → Mine mål (alle aktive og arkiverede mål)
- Indstillinger → Buer / Pilset / Baner (udstyrsstyring)

**Ret til dataportabilitet (Art. 20):** Brug
**Indstillinger → Eksportér mine data** for at downloade alle dine data som
en JSON-fil. Filen kan deles via telefonens delemenu til e-mail, AirDrop, Filer,
Google Drive osv. Dette er din komplette skydehistorik i et standardformat.

**Ret til sletning (Art. 17):**
- *Slet enkelt pas:* stryg passet på hjemmeskærmen → Slet
- *Slet alle data:* afinstallér JacArrow — både iOS og Android sletter
  automatisk hele SQLite-databasen og AsyncStorage. Kvitteringen for et Pro-køb
  opbevares af den butik, du købte i (Apple eller Google), og af RevenueCat til
  refusion og support.

**Ret til begrænsning og indsigelse (Art. 18–21):** JacArrow træffer
ingen automatiserede beslutninger om dig. Smart Insights-motoren analyserer kun
dine egne træningsdata lokalt på din enhed og præsenterer
observationer — den træffer ingen beslutninger på dine vegne.

**Ret til at trække samtykke tilbage (Art. 7):** Analyse-samtykket til Apple og
Google styres i telefonens egne indstillinger (se «Analyse- og nedbrudsdata fra
operativsystemet» ovenfor). Nedbrudsrapportering til Sentry slås fra i JacArrow
under **Indstillinger → Privatliv**. RevenueCat-data slettes, når du sletter det
Apple-ID eller den Google-konto, købet blev foretaget med.

---

## Ændringer

Vi opdaterer denne politik, når der sker væsentlige ændringer i, hvordan vi
behandler data. Ændringer kommunikeres via:
1. Datoen «Sidst opdateret» øverst på denne side
2. In-app-banner ved første åbning efter opdatering, hvis ændringen er væsentlig
   (fx nye tredjeparter, ny dataindsamling)

---

## Klager

Hvis du mener, at vi behandler dine personoplysninger i strid med GDPR, har du
ret til at klage til din nationale tilsynsmyndighed:

- **Danmark:** [Datatilsynet](https://www.datatilsynet.dk/)
- **EU/EØS:** find din myndighed på
  [edpb.europa.eu](https://www.edpb.europa.eu/about-edpb/about-edpb/members_en)

Vi opfordrer dig til at kontakte os først på galge.vender.0a@icloud.com — vi tager
alle privatlivshenvendelser alvorligt.
