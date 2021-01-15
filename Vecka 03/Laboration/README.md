# Laboration - Objektorienterad programmering

Denna laboration innehåller ett antal övningsuppgifter som relaterar till objektorienterad programmering med JavaScript.

## Objektlitteral

Användning av objektlitteraler inom JavaScript är vanligt förekommande. Arbetsmetodiken kan exempelvis användas inom objektorienterad JavaScript i syfte att skapa objekt, eller simulera klasser med statiskt innehåll. Då objektlitteraler deklareras på samma sätt oavsett vilken ECMAScript-specifikation som används, är det valfritt vilken specifikation som skall användas för att lösa laborationsuppgiften.

### Uppgiftsbeskrivning

Skapa en applikation som uppfyller samtliga punkter:

- **Statisk klass**; *skapa objektet `Person` i syfte att simulera en klass med statiskt innehåll. Då objektet simulerar en klass, bör det namnges med inledande versal.*
- **Egenskaper**; *ge klassen egenskaperna `firstname` och `lastname`. Egenskaperna skall deklareras som strängvärden med valfritt initialt värde (inte `null` eller `""`).*
- **Metod**; klassen skall innehålla metoden `sayHello()` som vid anrop, skriver ut en hälsningsfras i felsökningskonsollen som inkluderar tidigare nämnda egenskaper. Exempel på hälsningsfras: `"Hello, my name is firstname lastname"`. 
- **Exekvering**; *När programmet exekveras skall metoden `sayHello()` (automatiskt) anropas, och tidigare konstruerad hälsningsfras skrivs ut i felsökningskonsollen.*

### Frågeställningar

Fundera över följande frågeställningar:

- **Statisk**; *varför är denna arbetsmetodik förknippad med statisk (`static`) data?*
- **Instansiering**; *är det möjligt att via `new`-operatorn skapa nya objektinstanser av objektlitteralen?*
- **Åtkomstmodifierare**; *är det möjligt att skydda delar av objektlitteralens innehåll? Försök att deklarera `firstname` och `lastname` med skyddad åtkomst. Detta skulle innebära att egenskaperna inte kan modifieras utanför objektliteralen, men fortfarande skrivas ut via `sayHello`-metoden.*
- **Omfång**; *är det möjligt att från objektliteralens metod, anropa information i en annan objektliteral?*

### Resurser

Länkar till externa hjälpresurser:

- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Object_initializer

## Dynamisk klass

Dynamiska klasser är menade att användas i form av objekt. I JavaScript kan dynamiska klasser skapas på två sätt; enligt ECMAScript 5- eller ECMAScript 6-specifikation. Valfri specifikation kan användas för att lösa denna laborationsuppgift, men ECMAScript 5 är det rekommenderade alternativet. Rekommendationen baseras på att ECMAScript 5-varianten förutsätter mer kunskap om JavaScripts struktur och uppbyggnad.

### Uppgiftsbeskrivning

Skapa en applikation som uppfyller samtliga punkter:

- **Dynamisk klass**; *skapa klassen `Person` i syfte att simulera en, eller flera personer.*
- **konstruktor**; *klassens konstruktor tar emot två parametrar; `firstname` och `lastname`. Dessa parametrar är strängvärden.*
- **Egenskaper**; *ge klassen egenskaperna `firstname` och `lastname`. Egenskaperna skall deklareras som strängvärden och ges respektive värde från bifogade konstruktorparametrar.*
- **Metod**; *klassen skall innehålla metoden `sayHello()` som vid anrop, skriver ut en hälsningsfras i felsökningskonsollen som inkluderar tidigare nämnda egenskaper. Exempel på hälsningsfras: `"Hello, my name is firstname lastname"`.* 
- **Exekvering**; *När programmet exekveras skall två Person-objekt med valfri namn skapas. Kontrollera att objekten fungerar korrekt genom att anropa `sayHello()` på respektive objekt.*

### Frågeställningar

Fundera över följande frågeställningar:

- **Webbkomponenter**; *fundera över hur konceptet med objekt kan användas för att representera webbkomponenter, exempelvis som enskilda kommentarer, gillar-knappar, navigationsmenyer, mm..*

### Resurser

Länkar till externa hjälpresurser:

- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes
- https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Object-oriented_JS