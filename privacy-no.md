# Personvernerklæring — JacArrow

**Sist oppdatert:** 2026-08-22
**Behandlingsansvarlig:** Morten Jacobsen, Norge
**Kontakt:** galge.vender.0a@icloud.com

---

## Kort versjon

JacArrow lagrer **all dine data lokalt på enheten din**. Vi har ingen
servere som mottar dine skytinger, økter eller målsetting. Når du
avinstallerer appen forsvinner all data.

De eneste tredjepartene som mottar informasjon er:
- **Apple** (hvis du bruker appen på iPhone) — håndterer App Store-kjøp
- **Google** (hvis du bruker appen på Android) — håndterer Google Play-kjøp
- **RevenueCat** (etter du har kjøpt Pro) — verifiserer kjøpet
- **Sentry** (kun hvis du aktiverer krasj-rapportering) — mottar anonyme krasjdata for å hjelpe oss å fikse feil

Hvilken av Apple og Google som er involvert avhenger av hvilken butikk du
lastet ned appen fra. Ingen av dem er involvert i selve skytte-dataene dine.

Du har full rett til innsyn, sletting og dataportabilitet under GDPR.

---

## Hva vi lagrer

### På enheten din (lokalt, forlater aldri telefonen)
- **Skytte-data:** økter, runder, pile-plasseringer, score, tagger, mål, buer og pilesett
- **Innstillinger:** valgt språk, tema, dominant hånd, konkurranseklasse, varslings-toggles
- **Apphistorikk:** coach-mark-status (hvilke tips du har sett), tutorial-fullført-flagg

All denne data er lagret i SQLite-database og AsyncStorage på telefonen din.
Hverken JacArrow eller noen tredjepart har tilgang til denne dataen. Det
finnes ingen brukerkonto, ingen skylagring og ingen synkronisering mellom
enheter — data ligger på den enheten du registrerte den på.

### Varsler (lages lokalt på enheten)
JacArrow kan sende deg varsler: at du har satt personlig rekord, at
prøveperioden nærmer seg slutten, eller påminnelser om målene dine.

Alle disse varslene **planlegges lokalt på enheten din** og regnes ut fra
data som aldri forlater den. Vi har ingen server som sender varsler, og vi
mottar aldri noe varsel-token, noen leveringsbekreftelse eller noen
opplysning om hva du gjorde med varselet. Selve leveringen håndteres av
operativsystemet på telefonen (iOS eller Android), på samme måte som en
alarm du selv har satt.

Du kan skru av varsler når som helst — både i JacArrow under
**Innstillinger → Varsler**, og i telefonens egne innstillinger.

---

## Tredjeparter

### Apple App Store (på iPhone)
Har du lastet ned JacArrow fra App Store, håndteres alle in-app-kjøp av
Apple. Vi mottar aldri kortinformasjon, adresser, eller andre
betalings-detaljer. Apples
[personvernerklæring](https://www.apple.com/no/legal/privacy/) gjelder for
kjøps-flyten.

### Google Play (på Android)
Har du lastet ned JacArrow fra Google Play, håndteres alle in-app-kjøp av
Google via Google Play Billing. Vi mottar aldri kortinformasjon, adresser,
eller andre betalings-detaljer — vi får kun beskjed om at et kjøp er
gjennomført og gyldig. Googles
[personvernerklæring](https://policies.google.com/privacy?hl=no) gjelder for
kjøps-flyten.

Merk at Google Play, i motsetning til App Store, **ikke** deler et in-app-kjøp
videre til en familiegruppe. Det er en forskjell i butikkene, ikke noe vi
kan styre.

### RevenueCat (kun etter Pro-kjøp)
Når du kjøper JacArrow Pro registrerer RevenueCat din kvittering og en
anonym `appUserId` (UUID generert på enheten din). Dette er nødvendig for at
appen skal kunne verifisere ditt kjøp ved senere bruk og ved «Gjenopprett
kjøp». Kvitteringen kommer fra App Store eller Google Play, avhengig av hvor
du kjøpte. RevenueCats [personvernerklæring](https://www.revenuecat.com/privacy)
gjelder. Vi sender aldri ditt navn, e-post, eller andre personopplysninger.

### Analyse og krasjdata fra operativsystemet
Både Apple og Google kan sende utviklere anonyme, aggregerte tall om bruk og
krasj — men bare hvis **du** har slått det på i telefonens egne
innstillinger. Dette er butikkens funksjon, ikke vår: vi ser kun summer, aldri
noe som kan spores til deg. Vi bruker det til feilretting og
ytelses-optimering.

- **iPhone:** styres av «Del app-analyse». Skru av via
  **Innstillinger → Personvern og sikkerhet → Analyse og forbedringer**.
- **Android:** styres av «Bruk og diagnostikk». Skru av via
  **Innstillinger → Google → Bruk og diagnostikk** (navnet varierer litt
  mellom produsenter).

### Sentry (kun hvis du har aktivert krasj-rapportering)
Sentry er en feilovervåkings-tjeneste som hjelper oss å identifisere og
fikse feil i JacArrow. Sentry mottar kun data hvis du har **eksplisitt
aktivert** funksjonen via **Innstillinger → Personvern → Krasj-rapporter**
(toggle-en er AV som standard).

Når aktivert, sendes følgende til Sentrys EU-servere (Tyskland):
- Stack traces for krasj (filnavn, linjenumre, exception-typer)
- Enhetsmodell og operativsystem-versjon (iOS eller Android)
- App-versjon og build-nummer

Vi sender **ikke**:
- Personopplysninger (ingen navn, e-post, eller bruker-ID koblet til identitet)
- Performance-traces eller transaksjoner (`tracesSampleRate: 0`)
- IP-adresser (`sendDefaultPii: false`)

Du kan deaktivere krasj-rapportering når som helst via samme toggle. Når
deaktivert er Sentry **ikke initialisert** og ingen nettverkskall gjøres.
Sentrys [personvernerklæring](https://sentry.io/privacy/) gjelder for
mottatte data.

---

## Det vi IKKE samler

- Ingen brukerkonto, e-postadresse, eller passord
- Ingen skylagring, backup til våre servere, eller synkronisering mellom enheter
- Ingen GPS- eller lokasjons-data
- Ingen tilgang til kontakter, kalender, kamera eller mikrofon
- Ingen tredjeparts trackers (Firebase Analytics, Google Analytics, Facebook Pixel, osv.)
- Ingen reklame-identifikatorer (IDFA på iOS, annonse-ID på Android)
- Ingen videooppfølging eller fingerprinting

---

## Dine rettigheter (GDPR)

Du har følgende rettigheter under personvernforordningen:

**Innsyn (Art. 15):** All din data ligger lokalt på enheten. Du har full
innsikt via:
- Innstillinger → Mine økter (alle historiske runder)
- Innstillinger → Mine mål (alle aktive og arkiverte mål)
- Innstillinger → Buer / Pilesett / Lokasjoner (utstyrshåndtering)

**Dataportabilitet (Art. 20):** Bruk
**Innstillinger → Eksporter mine data** for å laste ned all din data som
JSON-fil. Filen kan deles via telefonens delings-meny til e-post, AirDrop,
Filer, Google Drive, osv. Dette er din komplette skytte-historikk i et
standard format.

**Sletting (Art. 17):**
- *Slett enkelt-økt:* sveip økten på hjem-skjermen → Slett
- *Slett alle data:* avinstaller JacArrow — både iOS og Android sletter
  automatisk hele SQLite-databasen og AsyncStorage. Kvitteringen for et
  Pro-kjøp beholdes hos butikken du kjøpte i (Apple eller Google) og hos
  RevenueCat for refund- og support-formål.

**Begrensning og innsigelse (Art. 18–21):** JacArrow utfører ingen
automatiserte beslutninger om deg. Smart innsikt-motoren analyserer kun din
egen treningsdata lokalt på enheten og presenterer observasjoner — den tar
ingen beslutninger på dine vegne.

**Trekk samtykke tilbake (Art. 7):** Analyse-samtykket til Apple og Google
styres i telefonens egne innstillinger (se «Analyse og krasjdata fra
operativsystemet» over). Krasj-rapportering til Sentry skrus av i JacArrow
under **Innstillinger → Personvern**. RevenueCat-data slettes når du sletter
Apple-ID-en eller Google-kontoen kjøpet ble gjort med.

---

## Endringer

Vi vil oppdatere denne erklæringen ved vesentlige endringer i hvordan vi
behandler data. Endringer kommuniseres via:
1. «Sist oppdatert»-dato på toppen av denne siden
2. In-app-banner ved første åpning etter oppdatering hvis endringen er
   vesentlig (eks. nye tredjeparter, ny datainnsamling)

---

## Klage

Hvis du mener vi behandler dine personopplysninger i strid med GDPR har du
rett til å klage til [Datatilsynet](https://www.datatilsynet.no/). Du
oppfordres til å kontakte oss først på galge.vender.0a@icloud.com — vi tar alle
henvendelser om personvern på alvor.
