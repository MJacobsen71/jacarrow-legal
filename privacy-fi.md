# Tietosuojakäytäntö — JacArrow

**Viimeksi päivitetty:** 2026-08-22
**Rekisterinpitäjä:** Morten Jacobsen, Norja
**Yhteystiedot:** galge.vender.0a@icloud.com

---

## Lyhyt versio

JacArrow tallentaa **kaikki tietosi paikallisesti laitteellesi**. Meillä ei ole
palvelimia, jotka vastaanottaisivat ammuntojasi, harjoituksiasi tai tavoitteitasi. Kun
poistat sovelluksen, kaikki tiedot katoavat.

Ainoat kolmannet osapuolet, jotka saavat tietoja, ovat:
- **Apple** (jos käytät sovellusta iPhonella) — käsittelee App Store -ostot
- **Google** (jos käytät sovellusta Androidilla) — käsittelee Google Play -ostot
- **RevenueCat** (Pro-oston jälkeen) — varmistaa ostosi
- **Sentry** (vain jos otat kaatumisraportit käyttöön) — vastaanottaa anonyymejä kaatumistietoja, jotta voimme korjata virheitä

Kumpi näistä — Apple vai Google — on osallisena, riippuu siitä, mistä kaupasta
latasit sovelluksen. Kumpikaan ei ole osallisena itse ammuntatiedoissasi.

Sinulla on täydet GDPR-oikeudet pääsyyn, poistoon ja tietojen siirrettävyyteen.

---

## Mitä tallennamme

### Laitteellasi (paikallisesti, ei poistu puhelimesta)
- **Ammuntatiedot:** harjoitukset, kierrokset, nuolten sijoittelut, pisteet, tunnisteet, tavoitteet, jouset ja nuolisetit
- **Asetukset:** valittu kieli, teema, ampumakäsi, kilpailuluokka, ilmoitusasetukset
- **Sovellushistoria:** coach-mark-tila (mitä vinkkejä olet nähnyt), tutoriaali-suoritettu-liput

Kaikki nämä tiedot tallennetaan SQLite-tietokantaan ja AsyncStorageen
puhelimellesi. Sen enempää JacArrowilla kuin millään kolmannella osapuolella ei
ole pääsyä näihin tietoihin. Käyttäjätiliä ei ole, pilvitallennusta ei ole eikä
laitteiden välistä synkronointia ole — tietosi pysyvät sillä laitteella, jolle
ne kirjasit.

### Ilmoitukset (ajastetaan paikallisesti laitteella)
JacArrow voi lähettää sinulle ilmoituksia: että olet tehnyt henkilökohtaisen
ennätyksen, että kokeilujaksosi on päättymässä, tai muistutuksia tavoitteistasi.

Kaikki nämä **ajastetaan paikallisesti laitteellasi** ja lasketaan tiedoista,
jotka eivät koskaan poistu siltä. Meillä ei ole palvelinta, joka lähettäisi
ilmoituksia, emmekä koskaan vastaanota ilmoitustunnusta, toimitusvahvistusta tai
mitään tietoa siitä, mitä teit ilmoitukselle. Itse toimituksen hoitaa puhelimen
käyttöjärjestelmä (iOS tai Android), täsmälleen kuten itse asettamasi herätys.

Voit ottaa ilmoitukset pois käytöstä milloin tahansa — sekä JacArrowissa kohdasta
**Asetukset → Ilmoitukset** että puhelimen omista asetuksista.

---

## Kolmannet osapuolet

### Apple App Store (iPhonella)
Jos latasit JacArrowin App Storesta, kaikki sovelluksen sisäiset ostot hoitaa
Apple. Emme koskaan vastaanota korttitietoja, osoitteita tai muita maksutietoja.
Applen [tietosuojakäytäntö](https://www.apple.com/fi/legal/privacy/) koskee
ostoprosessia.

### Google Play (Androidilla)
Jos latasit JacArrowin Google Playstä, kaikki sovelluksen sisäiset ostot hoitaa
Google Google Play Billingin kautta. Emme koskaan vastaanota korttitietoja,
osoitteita tai muita maksutietoja — meille kerrotaan vain, että osto on tehty ja
voimassa. Googlen
[tietosuojakäytäntö](https://policies.google.com/privacy?hl=fi) koskee
ostoprosessia.

Huomaa, että Google Play **ei** — toisin kuin App Store — jaa sovelluksen
sisäistä ostoa perheryhmälle. Se on kauppojen välinen ero, ei jotain mihin me
voimme vaikuttaa.

### RevenueCat (vain Pro-oston jälkeen)
Kun ostat JacArrow Pron, RevenueCat tallentaa kuittisi ja
anonyymin `appUserId`:n (laitteellasi luotu UUID). Tämä on tarpeen
sovelluksen ostosi varmistamiseen myöhemmässä käytössä ja «Palauta
ostot» -toiminnossa. Kuitti tulee App Storesta tai Google Playstä sen mukaan,
mistä ostit. RevenueCatin
[tietosuojakäytäntö](https://www.revenuecat.com/privacy) koskee tätä. Emme koskaan lähetä
nimeäsi, sähköpostiosoitettasi tai muita henkilötietoja.

### Käyttöjärjestelmän analytiikka- ja kaatumistiedot
Sekä Apple että Google voivat lähettää kehittäjille anonyymejä, koostettuja
lukuja käytöstä ja kaatumisista — mutta vain jos **sinä** olet ottanut sen
käyttöön puhelimen omista asetuksista. Se on kaupan toiminto, ei meidän: näemme
vain summia, emme koskaan mitään sinuun jäljitettävää. Käytämme sitä
virheenkorjaukseen ja suorituskyvyn optimointiin.

- **iPhone:** hallitaan «Jaa sovelluksen analyysit» -asetuksella. Ota pois
  käytöstä: **Asetukset → Tietosuoja ja turvallisuus → Analytiikka ja parannukset**.
- **Android:** hallitaan «Käyttö ja diagnostiikka» -asetuksella. Ota pois
  käytöstä: **Asetukset → Google → Käyttö ja diagnostiikka** (nimi vaihtelee
  hieman valmistajien välillä).

### Sentry (vain jos olet ottanut kaatumisraportit käyttöön)
Sentry on virheidenseurantapalvelu, joka auttaa meitä tunnistamaan ja korjaamaan
virheitä JacArrowissa. Sentry vastaanottaa tietoja vain, jos olet antanut siihen
**nimenomaisen suostumuksen** kohdasta **Asetukset → Tietosuoja → Kaatumisraportit**
(kytkin on oletuksena POIS päältä).

Kun ominaisuus on käytössä, Sentryn EU-palvelimille (Saksa) lähetetään seuraavat:
- Kaatumisten pinojäljet (tiedostonimet, rivinumerot, poikkeustyypit)
- Laitemalli ja käyttöjärjestelmän versio (iOS tai Android)
- Sovellusversio ja build-numero

Emme lähetä:
- Henkilökohtaisia tietoja (ei nimeä, ei sähköpostia, ei identiteettiin liitettyä käyttäjätunnusta)
- Suorituskykyjälkiä tai tapahtumia (`tracesSampleRate: 0`)
- IP-osoitteita (`sendDefaultPii: false`)

Voit poistaa kaatumisraportit käytöstä milloin tahansa samalla kytkimellä. Kun ominaisuus on
poissa käytöstä, Sentryä **ei alusteta** eikä verkkopyyntöjä tehdä.
Sentryn [tietosuojakäytäntö](https://sentry.io/privacy/) koskee vastaanotettuja tietoja.

---

## Mitä EMME kerää

- Ei käyttäjätiliä, sähköpostiosoitetta tai salasanaa
- Ei pilvitallennusta, ei varmuuskopiointia palvelimillemme, ei laitteiden välistä synkronointia
- Ei GPS- tai sijaintitietoja
- Ei pääsyä yhteystietoihin, kalenteriin, kameraan tai mikrofoniin
- Ei kolmansien osapuolten seurantoja (Firebase Analytics, Google Analytics, Facebook Pixel jne.)
- Ei mainostunnisteita (IDFA iOS:ssä, mainostunnus Androidissa)
- Ei video-seurantaa eikä laitteen sormenjälkeä

---

## Oikeutesi (GDPR)

Sinulla on seuraavat oikeudet yleisen tietosuoja-asetuksen mukaan:

**Oikeus tutustua tietoihin (Art. 15):** Kaikki tietosi on tallennettu paikallisesti laitteellesi.
Sinulla on täysi näkyvyys:
- Asetukset → Omat harjoitukset (kaikki historialliset kierrokset)
- Asetukset → Omat tavoitteet (kaikki aktiiviset ja arkistoidut tavoitteet)
- Asetukset → Jouset / Nuolisetit / Ammuntapaikat (varustehallinta)

**Oikeus tietojen siirrettävyyteen (Art. 20):** Käytä
**Asetukset → Vie tietoni** ladataksesi kaikki tietosi JSON-tiedostona. Tiedosto
voidaan jakaa puhelimen jakovalikon kautta sähköpostiin, AirDropiin,
Tiedostoihin, Google Driveen jne. Tämä on täydellinen ammuntahistoriasi
standardimuodossa.

**Oikeus tietojen poistamiseen (Art. 17):**
- *Poista yksittäinen harjoitus:* pyyhkäise harjoitusta aloitusnäytössä → Poista
- *Poista kaikki tiedot:* poista JacArrow — sekä iOS että Android poistavat
  automaattisesti koko SQLite-tietokannan ja AsyncStoragen. Pro-oston kuitti
  säilyy siinä kaupassa, josta ostit (Apple tai Google), ja RevenueCatilla
  palautus- ja tukitarpeisiin.

**Oikeus käsittelyn rajoittamiseen ja vastustamiseen (Art. 18–21):** JacArrow ei tee
mitään automatisoituja päätöksiä sinusta. Smart Insights -moottori analysoi vain
omia harjoitustietojasi paikallisesti laitteellasi ja esittää
havaintoja — se ei tee päätöksiä puolestasi.

**Oikeus peruuttaa suostumus (Art. 7):** Applen ja Googlen analytiikkasuostumus
hallitaan puhelimen omista asetuksista (ks. «Käyttöjärjestelmän analytiikka- ja
kaatumistiedot» yllä). Kaatumisraportointi Sentryyn otetaan pois käytöstä
JacArrowissa kohdasta **Asetukset → Tietosuoja**. RevenueCat-tiedot poistetaan,
kun poistat sen Apple-ID:n tai Google-tilin, jolla osto tehtiin.

---

## Muutokset

Päivitämme tätä käytäntöä, kun tapahtuu merkittäviä muutoksia siinä, miten käsittelemme
tietoja. Muutoksista viestitään:
1. Sivun yläosan «Viimeksi päivitetty» -päivämäärän kautta
2. Sovelluksensisäisen bannerin kautta päivityksen jälkeisellä ensimmäisellä käynnistyksellä, jos muutos on merkittävä
   (esim. uudet kolmannet osapuolet, uusi tiedonkeruu)

---

## Valitukset

Jos uskot, että käsittelemme henkilötietojasi GDPR:n vastaisesti, sinulla on
oikeus tehdä valitus kansalliselle tietosuojaviranomaisellesi:

- **Suomi:** [Tietosuojavaltuutetun toimisto](https://tietosuoja.fi/)
- **EU/ETA:** löydä viranomaisesi osoitteesta
  [edpb.europa.eu](https://www.edpb.europa.eu/about-edpb/about-edpb/members_en)

Suosittelemme ottamaan yhteyttä meihin ensin osoitteessa galge.vender.0a@icloud.com — otamme
kaikki tietosuojakyselyt vakavasti.
