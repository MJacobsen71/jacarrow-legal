# Support — JacArrow

**Senast uppdaterad:** 2026-08-22
**Version som omfattas:** v1.0+
**Kontakt:** galge.vender.0a@icloud.com

---

## Snabb hjälp

### Hur registrerar jag en serie?

1. Öppna JacArrow → tryck **Nytt pass** på Hem-fliken
2. Välj bana, tavla och omgångsformat → tryck **Starta pass**
3. **Tryck på tavlan** för att placera varje pil — använd pinch-zoom och precisionsluppen för noggrannhet
4. Tryck **Spara serie** när alla pilar är placerade
5. Upprepa för varje serie tills omgången är klar

### Vad är skillnaden mellan X och 10?

X-ringen är den innersta ringen och ger 10 poäng — samma som 10-ringen. JacArrow spårar X separat eftersom X används som avgörande vid lika resultat i tävlingar. Tryck «X»-knappen när en pil träffar X-ringen i score-pad-läge.

### Hur korrigerar jag en felplacerad pil?

1. Långtryck på pilen på tavlan → precisionsluppen aktiveras
2. Dra pilen till den nya positionen → släpp
3. ELLER tryck på pilen för att välja den → tryck **Ta bort** för att ta bort den

I score-pad-läge: tryck på pilbadgen i score-pad och välj ett nytt värde.

### Vad är efterregistrering (📋-ikonen)?

📋-ikonen markerar pass som matats in manuellt med score-pad, inte registrerade på tavlan med koordinater. Träffkarta, konstellation och spridningsanalys är inte tillgängliga för efterregistrerade pass — endast poängsummorna.

### Hur köper jag Pro?

1. Tryck på en Pro-låst funktion (t.ex. ett tema med Pro-märke)
2. Paywall visas med knappen **Köp Pro (299 NOK)**
3. Butikens köpdialog visas → bekräfta (Face ID / lösenord på iPhone, Google-konto på Android)
4. Pro aktiveras direkt — alla funktioner låses upp

**Pris:** 299 NOK engångsköp, livstid. Ingen prenumeration, inga återkommande debiteringar.

### Hur återställer jag köp på ny telefon?

1. Ladda ner JacArrow på den nya telefonen (gratisversionen)
2. Logga in med samma konto du köpte Pro med — Apple-ID på iPhone, Google-konto på Android
3. Öppna JacArrow → **Inställningar → Licens → Återställ köp**
4. Pro återaktiveras automatiskt

Ett köp kan inte flyttas mellan plattformarna: har du köpt Pro på iPhone gäller det inte på en Android-telefon, och omvänt. Butikerna tillåter det inte. Har du bytt Apple-ID eller Google-konto: kontakta galge.vender.0a@icloud.com så hjälper vi dig.

### Hur exporterar jag mina data?

**Inställningar → Om appen → Exportera mina data** → telefonens delningsmeny visas. Välj AirDrop, Mail, Filer, Google Drive eller var du vill skicka JSON-filen.

JSON-filen innehåller alla pass, omgångar, pilar, mål, båguppsättningar och inställningar — full portabilitet enligt GDPR Art. 20.

### Hur tar jag bort all min data?

Avinstallera JacArrow → både iOS och Android tar automatiskt bort hela SQLite-databasen och alla inställningar. Inga restdata finns kvar på enheten.

Om du har köpt Pro: kvittot finns kvar hos den butik du köpte i — Apple eller Google (för återbetalnings- och supportändamål). Avinstallation påverkar inte framtida ominstallationer — Pro återaktiveras automatiskt via Återställ köp.

### Vilka omgångsformat stöds?

- **WA 720** (utomhus, 6 serier × 12 pilar = 72 pilar)
- **WA 18 m inomhus** (10 serier × 3 pilar)
- **WA 1440** (4 sekvensiella distanser)
- **Vegas Shoot** (10 serier × 3 pilar inomhus 18 m)
- **AGB Portsmouth** (10 serier × 3 pilar inomhus 20 yd)
- **NFAA Indoor** (12 serier × 5 pilar inomhus 20 yd)
- **Fri träning** (inga formatgränser)

Alla format följer officiell WA Book 3-efterlevnad: linjeregeln, separat X-spårning, korrekta ringradier.

### Vilka tavlor stöds?

- **WA 122 cm 10-ring** (utomhusstandard)
- **WA 80 cm 10-ring** (utomhus långdistans)
- **WA 40 cm 10-ring** (inomhus, enkel-spot)
- **WA 40 cm Vegas 3-spot triangulär** (inomhustävling)
- **WA 40 cm Vegas 3-spot vertikal** (inomhus alternativ)
- **AGB Portsmouth 60 cm 10-ring** (inomhus UK)
- **NFAA inomhus enkel-spot blå 40 cm** (USA)
- **NFAA inomhus 5-spot blå 40 cm** (USA-tävling)

---

## Tekniska problem

### Appen kraschar vid start

1. Stäng av telefonen och starta om
2. Om problemet kvarstår: avinstallera och installera om JacArrow (köpdata försvinner INTE — kvittot finns kvar hos butiken)
3. Skicka oss en beskrivning på galge.vender.0a@icloud.com — vad du gjorde precis före kraschen och vilken telefon du har

**iPhone:** du kan hitta kraschloggen själv och skicka med den: **Inställningar → Integritet och säkerhet → Analys och förbättringar → Analysdata** → hitta JacArrow-loggen → dela med oss. Har du «Dela app-analys» påslaget får vi kraschloggar automatiskt.

**Android:** krascher rapporteras automatiskt till oss om du har «Användning och diagnostik» påslaget i telefonens inställningar. Du behöver inte göra något mer än att beskriva vad som hände.

### Poängdata försvann efter uppdatering

JacArrow lagrar allt lokalt i SQLite. Uppdateringar migrerar databasen endast framåt — gamla data konverteras till nytt format, raderas aldrig.

Om du upplever dataförlust:
1. Verifiera att du är inloggad med samma konto som tidigare (Apple-ID eller Google-konto)
2. Kontrollera **Inställningar → Om appen → Versionsnummer** — är det den senaste?
3. Skicka oss en beskrivning till galge.vender.0a@icloud.com

Vi har en strikt regel om att publicerade migrationer är oföränderliga — dataförlust från uppdateringar ska aldrig hända. Om det händer har vi en bug och vi vill veta om det.

### Pinch-zoom fungerar inte på tavlan

1. Prova med två fingrar, inte ett
2. Kontrollera att du inte har minskad rörelse påslaget — **iPhone: Inställningar → Tillgänglighet → Rörelse**, **Android: Inställningar → Tillgänglighet → Ta bort animationer** — det kan begränsa gester i vissa appar
3. Stäng appen helt (svep upp från botten, svep JacArrow uppåt) och öppna igen

### Konstellationsvyn vibrerar vid dragning

Detta var en bug i v0.28.2 och tidigare — fixat i v0.28.3. Uppdatera appen till senaste versionen i App Store eller Google Play.

---

## Feedback och förfrågningar

### Föreslå en ny funktion

Skicka ett mejl till galge.vender.0a@icloud.com med:
- **Vad** du vill ha (kort beskrivning)
- **Varför** (vad skulle det förbättra i din träning?)
- **Hur ofta** du skulle använda det (dagligen / per pass / mer sällan)

Vi läser varenda förfrågan och publicerar prioriterade funktioner i appens «Nyheter»-flöde.

### Rapportera en bug

Skicka ett mejl till galge.vender.0a@icloud.com med:
- **Vad som gick fel** (så detaljerat du kan)
- **Vad du förväntade dig skulle hända**
- **Steg-för-steg** för att reproducera
- **Operativsystemversion och telefonmodell** (iPhone: Inställningar → Allmänt → Om · Android: Inställningar → Om telefonen)
- **JacArrow-version** (Inställningar → Om appen)
- Skärmdump om relevant

### Allmänt
Vi svarar på alla förfrågningar inom 3 arbetsdagar. Akuta problem (krascher som hindrar dig från att skjuta) prioriteras högre.

---

## GDPR och integritet

För fullständig integritetspolicy: [Integritet](https://mjacobsen71.github.io/jacarrow-legal/privacy-sv)

För att exportera dina data, ta bort ett pass eller utöva andra GDPR-rättigheter: se Integritetspolicyn.

Integritetsklagomål: kontakta oss **först** på galge.vender.0a@icloud.com. Om vi inte kan lösa ärendet kan du klaga hos din nationella dataskyddsmyndighet. För Sverige: [IMY](https://www.imy.se/).

---

## Om JacArrow

**Utvecklare:** Morten Jacobsen, Norge
**Hemsida:** [mjacobsen71.github.io/jacarrow-legal](https://mjacobsen71.github.io/jacarrow-legal)
**Integritetspolicy:** [Integritet](https://mjacobsen71.github.io/jacarrow-legal/privacy-sv)
**Licenser (öppen källkod):** se Inställningar → Om appen → Licenser i appen

JacArrow är ett solo-utvecklarprojekt byggt för bågskyttar på alla nivåer — från din första pil till din hundrade tävling. WA Book 3-kompatibel poängräkning finns från dag ett, redo när du vill. Byggt med React Native + Expo + TypeScript + SQLite. Ingen backend, inget moln, ingen spårning.

Tack för att du använder appen. 🏹
