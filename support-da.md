# Support — JacArrow

**Sidst opdateret:** 2026-08-22
**Version dækket:** v1.0+
**Kontakt:** galge.vender.0a@icloud.com

---

## Hurtig hjælp

### Hvordan registrerer jeg en serie?

1. Åbn JacArrow → tryk **Nyt pas** på Hjem-fanen
2. Vælg bane, skive og runde-format → tryk **Start pas**
3. **Tryk på skiven** for at placere hver pil — brug pinch-zoom og præcisionsluppen for nøjagtighed
4. Tryk **Gem serie**, når alle pile er placeret
5. Gentag for hver serie, indtil runden er færdig

### Hvad er forskellen på X og 10?

X-ringen er den inderste ring og giver 10 point — det samme som 10-ringen. JacArrow registrerer X separat, fordi X bruges som omkamp i konkurrencer. Tryk «X»-knappen, når en pil rammer X-ringen i score-pad-tilstand.

### Hvordan retter jeg en fejlplaceret pil?

1. Langt tryk på pilen på skiven → præcisionsluppen aktiveres
2. Træk pilen til den nye position → slip
3. ELLER tryk på pilen for at vælge den → tryk **Slet** for at fjerne den

I score-pad-tilstand: tryk på pil-badgen i score-pad og vælg en ny værdi.

### Hvad er efterregistrering (📋-ikonet)?

📋-ikonet markerer pas, der er indtastet manuelt med score-pad'en, ikke registreret på skiven med koordinater. Trækort, konstellation og spredningsanalyse er ikke tilgængelige for efterregistrerede pas — kun pointsummerne.

### Hvordan køber jeg Pro?

1. Tryk på en Pro-låst funktion (fx et tema med Pro-mærke)
2. Paywall'en vises med knappen **Køb Pro (299 NOK)**
3. Butikkens købsvindue vises → bekræft (Face ID / kode på iPhone, Google-konto på Android)
4. Pro aktiveres med det samme — alle funktioner låses op

**Pris:** 299 NOK engangskøb, livstid. Intet abonnement, ingen tilbagevendende opkrævninger.

### Hvordan gendanner jeg køb på en ny telefon?

1. Download JacArrow på den nye telefon (gratis-versionen)
2. Log ind med samme konto, du købte Pro med — Apple-ID på iPhone, Google-konto på Android
3. Åbn JacArrow → **Indstillinger → Licens → Gendan køb**
4. Pro reaktiveres automatisk

Et køb kan ikke flyttes mellem platformene: har du købt Pro på iPhone, gælder det ikke på en Android-telefon, og omvendt. Butikkerne tillader det ikke. Har du skiftet Apple-ID eller Google-konto: kontakt galge.vender.0a@icloud.com, så hjælper vi dig.

### Hvordan eksporterer jeg mine data?

**Indstillinger → Om appen → Eksportér mine data** → telefonens delemenu kommer frem. Vælg AirDrop, Mail, Filer, Google Drive, eller hvorhen du vil sende JSON-filen.

JSON'en indeholder alle pas, runder, pile, mål, bue-opsætninger og indstillinger — fuld portabilitet efter GDPR Art. 20.

### Hvordan sletter jeg alle mine data?

Afinstallér JacArrow → både iOS og Android fjerner automatisk hele SQLite-databasen og alle indstillinger. Ingen restdata bliver tilbage på enheden.

Hvis du har købt Pro: kvitteringen forbliver hos den butik, du købte i — Apple eller Google (til refusion og support). Afinstallation påvirker ikke fremtidige geninstallationer — Pro reaktiveres automatisk via Gendan køb.

### Hvilke runde-formater understøttes?

- **WA 720** (udendørs, 6 serier × 12 pile = 72 pile)
- **WA 18 m indendørs** (10 serier × 3 pile)
- **WA 1440** (4 sekventielle distancer)
- **Vegas Shoot** (10 serier × 3 pile indendørs 18 m)
- **AGB Portsmouth** (10 serier × 3 pile indendørs 20 yd)
- **NFAA Indoor** (12 serier × 5 pile indendørs 20 yd)
- **Fri træning** (ingen formatgrænser)

Alle formater følger officiel WA Book 3-overholdelse: linjereglen, separat X-registrering, korrekte ringradier.

### Hvilke skiver understøttes?

- **WA 122 cm 10-ring** (udendørs standard)
- **WA 80 cm 10-ring** (udendørs lang distance)
- **WA 40 cm 10-ring** (indendørs, enkelt-spot)
- **WA 40 cm Vegas 3-spot triangulær** (indendørs konkurrence)
- **WA 40 cm Vegas 3-spot vertikal** (indendørs alternativ)
- **AGB Portsmouth 60 cm 10-ring** (indendørs UK)
- **NFAA indendørs enkelt-spot blå 40 cm** (USA)
- **NFAA indendørs 5-spot blå 40 cm** (USA-konkurrence)

---

## Tekniske problemer

### Appen crasher ved opstart

1. Sluk telefonen og tænd igen
2. Hvis problemet fortsætter: afinstallér og geninstallér JacArrow (købsdata mistes IKKE — kvitteringen forbliver hos butikken)
3. Send os en beskrivelse på galge.vender.0a@icloud.com — hvad du gjorde lige før nedbruddet, og hvilken telefon du har

**iPhone:** du kan selv finde crash-loggen og sende den med: **Indstillinger → Anonymitet og sikkerhed → Analyse og forbedringer → Analysedata** → find JacArrow-loggen → del med os. Har du «Del app-analyse» slået til, får vi crash-logs automatisk.

**Android:** nedbrud rapporteres automatisk til os, hvis du har «Brug og diagnosticering» slået til i telefonens indstillinger. Du behøver ikke gøre andet end at beskrive, hvad der skete.

### Pointdata forsvandt efter opdatering

JacArrow gemmer alt lokalt i SQLite. Opdateringer migrerer databasen kun fremad — gamle data konverteres til nyt format, slettes aldrig.

Hvis du oplever datatab:
1. Verificér, at du er logget ind med samme konto som før (Apple-ID eller Google-konto)
2. Tjek **Indstillinger → Om appen → Versionsnummer** — er det den nyeste?
3. Send os en beskrivelse på galge.vender.0a@icloud.com

Vi har en streng regel om, at offentliggjorte migrationer er uforanderlige — datatab fra opdateringer bør aldrig ske. Hvis det sker, har vi en bug, og vi vil gerne høre om det.

### Pinch-zoom virker ikke på skiven

1. Prøv med to fingre, ikke én
2. Tjek, at du ikke har reduceret bevægelse slået til — **iPhone: Indstillinger → Tilgængelighed → Bevægelse**, **Android: Indstillinger → Tilgængelighed → Fjern animationer** — det kan begrænse gestures i nogle apps
3. Luk appen helt (stryg op fra bunden, stryg JacArrow opad) og åbn igen

### Konstellationsvisningen vibrerer ved træk

Dette var en bug i v0.28.2 og tidligere — rettet i v0.28.3. Opdater appen til seneste version i App Store eller Google Play.

---

## Feedback og forespørgsler

### Foreslå en ny funktion

Send en e-mail til galge.vender.0a@icloud.com med:
- **Hvad** du vil have (kort beskrivelse)
- **Hvorfor** (hvad ville det forbedre i din træning?)
- **Hvor ofte** ville du bruge det (dagligt / pr. pas / sjældnere)

Vi læser hver eneste forespørgsel og udgiver prioriterede funktioner i appens «Nyheder»-stream.

### Rapportér en bug

Send en e-mail til galge.vender.0a@icloud.com med:
- **Hvad gik galt** (så detaljeret du kan)
- **Hvad du forventede skulle ske**
- **Trin-for-trin** for at reproducere
- **Operativsystemversion og telefonmodel** (iPhone: Indstillinger → Generelt → Om · Android: Indstillinger → Om telefonen)
- **JacArrow-version** (Indstillinger → Om appen)
- Skærmbillede hvis relevant

### Generelt
Vi svarer på alle henvendelser inden for 3 hverdage. Akutte problemer (crashes der hindrer dig i at skyde) prioriteres højere.

---

## GDPR og privatliv

For fuld privatlivspolitik: [Privatliv](https://mjacobsen71.github.io/jacarrow-legal/privacy-da)

For at eksportere dine data, slette et pas eller udøve andre GDPR-rettigheder: se Privatlivspolitikken.

Privatlivsklager: kontakt os **først** på galge.vender.0a@icloud.com. Hvis vi ikke kan løse sagen, kan du klage til din nationale tilsynsmyndighed. For Danmark: [Datatilsynet](https://www.datatilsynet.dk/).

---

## Om JacArrow

**Udvikler:** Morten Jacobsen, Norge
**Hjemmeside:** [mjacobsen71.github.io/jacarrow-legal](https://mjacobsen71.github.io/jacarrow-legal)
**Privatlivspolitik:** [Privatliv](https://mjacobsen71.github.io/jacarrow-legal/privacy-da)
**Licenser (open source):** se Indstillinger → Om appen → Licenser i appen

JacArrow er et solo-udvikler-projekt bygget til bueskytter på alle niveauer — fra din første pil til din hundrede konkurrence. WA Book 3-kompatibel scoring er der fra dag ét, klar når du vil. Bygget med React Native + Expo + TypeScript + SQLite. Ingen backend, ingen sky, ingen sporing.

Tak fordi du bruger appen. 🏹
