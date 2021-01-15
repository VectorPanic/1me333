# 1ME333: Interaktionsdesign 3 - Inlämningsuppgift

Detta dokument är en uppgiftsbeskrivning för kursens övergripande inlämningsuppgift. Uppgiften syftar att examinera objektorienterad, sensordriven mjukvaruutveckling utifrån ett användarcentrerat perspektiv. Samtliga kursdeltagare skall individuellt, med hjälp av befintlig webbteknik, utveckla en egen applikation som inkluderar sensor- och/eller data från externa källor; exempelvis via öppna webbtjänster och/eller REST-APIer. Applikationen skall vara en progressiv webbapplikation (PWA), alternativt en skrivbordsapplikation som baseras på Electron-ramverket. Den tilltänkta applikationen är menad att fokusera på teorin bakom mikrointeraktion, och således erbjuda en möjligen minimalistisk, men väl genomtänkt användarupplevelse. Uppgiftens tidsfrist samt tid och plats för muntlig presentation, redogörs via kursens schema.

## Funktionella krav

Uppgiften är menad att ge kursdeltagare kreativt utrumme att utforma ett eget och unikt lösningsförslag, dock inom tydligt definerade gränser. 

Då kursdeltagare har tidigare erfarenhet av interaktiva medier och/eller webbteknologier, är uppgiftens kriterier uppdelade i funktionella krav för respektive inriktning. Utöver inriktningsspecifika krav som samtliga kursdeltagare skall uppnå. Ett lösningsförslag skall bestå av en färdig produkt och inte mockups eller prototyper.

En tilltänkt applikation skall:

- **Hämta och behandla data från extern datakälla och/eller enhetssensor**; *applikationen skall inte vara låst till en förbestämd datauppsättning. Färdigställd applikation hämtar/samlar in data under exekvering. Detta data kan komma från enhetssensorer (via tillgängliga lokala APIer) eller via externa REST-APIer.*
- **Applicera konceptet med mikrointeraktion**; *applikationen skall applicera ett eller flera av dom designprinciper som ingår i begreppet mikrointeraktion. Syftet är att förbättra användarupplevelsen.*

För möjlighet till väl godkänt betyg (VG) skall även följande krav uppfyllas:

- **Flera vyer**; *detta krav innebär att applikationen inte skall vara begränsad till en vy (skärm). Användare skall ha möjlighet att navigera inom applikationen och således växla mellan vyer.*
- **Lagra information och/eller inställningar**; *detta krav innebär att applikationen skall besitta förmåga att lagra användarrelaterad information i syfte att förvättra användarupplevelsen. Detta kan exempelvis består av sparade inställningar, historik, information som genererats/skapas av användaren, osv.*
- **Installationsbar**; *detta krav innebär att applikationen skall vara färdig att installeras på tilltänkt målplattform. Vid utveckling av Electron-baserad applikation, skall källkod med tillhörande resurser paketeras i körbar binärfil, komplett med associerad applikationsikon. Vid utveckling av PWA skall applikationen erbjuda ett applikationsmanifest och kunna installeras via PWA-teknik.*

### Interaktiva medier

Detta avsnitt innehåller krav som skall uppfyllas av kursdeltagare med inriktning mot interaktiva medier. Följande punkter är en förutsättning för godkänt (G) betyg:

- **Utforma ett gränssnitt med inslag av animation**; *applikationen skall använda animation i syfte att förbättra användarupplevelsen. Detta krav kan uppnås på flera olika sätt, exempelvis genom att applicera animation på: knappar och gränssnittskomponenter, laddningsskärmar, introduktionssekvenser, mm..*
- **Utveckla och implementera en grafisk profil**; *applikationen skall baseras på en grafisk profil som redovisas i den skriftliga rapporten. Den grafiska profilen representerar det grafiska regelverk som den tilltänkta applikationen skall följa. Detta inkluderar exempelvis färgval, design- och layoutregler samt applikationsikon och eventuell logotyp.*
- **Testa och analysera användarupplevens**; *under utvecklingen av applikationen skall minst två användartest genomföras och dokumenteras.*

### Webbteknologier

Detta avsnitt innehåller krav som skall uppfyllas av kursdeltagare med inriktning mot webbteknologier. Följande punkter är en förutsättning för godkänt (G) betyg:

- **Utforma en objektorienterad kodbas**; *applikationen skall konstrueras med en objektorienterad kodbas. Kursdeltagare har möjlighet att välja huruvida deras programkod skall utformas enligt ES5- eller ES6-specifikationen.*
- **Redogör för tillämpad implementation via UML-diagram**; *då applikationen utformas med en objektorienterad kodbas, kan UML-diagram vara ett lämpligt verktyg för att plannera och illustera applikationens uppbyggnad och struktur.*
- **Applicera felhantering inom den egna kodbasen**; *applikationen skall ha förmåga att hantera fel som eventuellt kan uppstå i samband med inläsning av sensor och/eller extern information. Exempelvis genom att informera användaren om eventuellt problem.*

## Rapport

Arbetsprocessen samt redovisat lösningsförslag, analyseras och dokumenteras i en akademisk rapport. Syftet är att redogöra för lösningsförslagets underliggande teknologi, samt den teoretiska kunskap som lett fram till dess aktuella utformning. Kursdeltagare skall beskriva hur deras lösningsförslag uppfyller uppgiftens funktionella, och inriktningsspecifik krav. Kursdeltagare använder adkademiska referenser enligt Harvardsystemet, för att hänvisa till externa dokument och/eller publikationer som styrker eller validerar teser eller designbeslut. Om arbetet innefattar användartester kan denna information användas som styrkande underlag; förutsatt att insamlad data redovisas i form av bilaga. Rapporter som saknar, eller felaktigt använder akademiska referenser, klassas som ofullständiga och resulterar således i ett underkänt betyg. Rapportens omfattning motsvarar tre till fem A4-sidor (1800-3000 ord) med redovisat textmaterial. Den slutgiltiga rapporten redovisas i PDF-format och inte arbetsformat som exempelvis DOC, DOCX eller ODT.

### Namngivningskonvention

För att påskynda granskningsprocessen samt minska risken för ihopblandade filer  - används en namngivningskonvention. Vidare skall inlämnad rapport innehålla skribentens namn och personnummer. Inlämningsfil (komprimerade projektfiler) och akademisk rapport skall namnges efter följande system:

- Kurskod
- Marksträck
- Skribentens tre första bokstäver ur förnamnet
- Skribentens tre första bokstäver ur efternamnet

Om exempelvis skribenten Alfred Nobel redovisar sitt lösningsförslag, namnger han sin inlämningsfil: `1me333_alfnob.zip`. Notera att denna inlämningsfil innehåller samtliga projektfiler samt filen `1me333_alfnob.pdf` som innehåller den skriftliga rapporten.

## Uppgiftsredovisning

Uppgiften redovisas via två obligatoriska moment; elektronisk inlämning samt muntlig presentation. Färdigställda lösningsförslag laddas upp till inlämningsmappen på lärplattformen FirstClass. En inlämning inkluderar samtliga projektfiler samt bifogad akademisk rapport. Filer paketeras i lämpligt komprimeringsformatet, exempelvis zip. Tidsfrist för inlämning finns redovisat i kursens schema.

Utöver inlämning av projektfiler och skriftlig rapport, genomförs en muntlig presentation där respektive kursdeltagare presenterar sitt lösningsförslag. En presentation genomförs med lämpligt presentationsverktyg i syfte att illustrera den produkt som framställts under kursens gång. Maximal presentationstid per kursdeltagar är 15 minuter. Efter avslutad presentation, kan övriga kursdeltagare ställa frågor och under ca fem minuter, för en diskussion gällande det arbete som presenterats.

## Betygskriterier

Inlämnade lösningsförslag betygssätts enligt följande betygsskala:

- **Underkänt betyg (U)**; det inlämnade lösningsförslaget uppfyller inte uppgiftsbeskrivningens generella och/eller inriktningsspecifika krav.
- **Underkänt med möjlighet till komplettering (UX)**; det inlämnade lösningsförslaget innehåller mindre brister som ges möjlighet att åtgärda under en kortare period, detta i syfte att komplettera till godkänt betyg.
- **Godkänt betyg (G)**; det inlämnade lösningsförslaget uppfyller uppgiftsbeskrivningens funktionella och inriktningsspecifika krav.
- **Väl godkänt betyg**; det inlämnade lösningsförslaget uppfyller uppgiftsbeskrivningens godkända och väl godkända krav.