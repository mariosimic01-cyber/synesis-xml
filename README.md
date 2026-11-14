# Synesis XML

Račun u XML za Synesis. Statična aplikacija bez instalacije i build koraka.

## 1. Objava na Vercelu (jednom)
1. Na github.com napravite novi repozitorij (npr. `synesis-xml`), pa u njega učitajte **sve datoteke i mapu `icons`** iz ove mape (Add file → Upload files).
2. Na vercel.com: Add New → Project → odaberite taj repozitorij → Deploy. Framework: Other. Build command i Output directory ostaju prazni.
3. Dobit ćete adresu poput `https://synesis-xml.vercel.app`.

## 2. Na iPhone (jednom)
1. Otvorite adresu u **Safariju**.
2. Podijeli → **Dodaj na početni zaslon**. Pojavit će se ikona „Synesis XML".
3. Otvorite aplikaciju s početnog zaslona. Ona se otvara preko cijelog zaslona, kao prava aplikacija.
4. Dodirnite zupčanik i upišite **Anthropic API ključ** (console.anthropic.com → API Keys). U Billing postavite mjesečni limit potrošnje.

## 3. Svakodnevno
1. **Slikaj račun** (ili Galerija / PDF).
2. Provjeri očitano. Crvena oznaka znači da se iznosi ne slažu s računom.
3. **Izvezi ZIP** → Spremi u Datoteke ili iCloud Drive → na računalu učitaj XML u Synesisu.

## Kupci
Pod **Novi** upišite naziv i OIB tvrtke, pa pritisnite **Spremi kupca** (znak diskete). Kupac ostaje zauvijek u popisu na tom uređaju i bira se jednim dodirom.

## Ažuriranje aplikacije
Zamijenite `index.html` (i po potrebi ostale datoteke) u GitHubu. Vercel sam objavi novu verziju. Na mobitelu potpuno zatvorite aplikaciju i otvorite je dva puta.

## Napomene
- Podaci (kupci, zapamćeni dobavljači, API ključ, nespremljeni računi) spremaju se samo u pregledniku na tom uređaju. Dok je aplikacija dodana na početni zaslon, iOS ih ne briše.
- Ako obrišete aplikaciju ili podatke web-stranica u Safariju, kupce treba ponovno unijeti.
- Izvoz ZIP-a koristi iPhoneov izbornik za dijeljenje.
