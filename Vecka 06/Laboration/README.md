# Laboration - Multimedia

Denna laboration innehåller ett antal övningsuppgifter gällande hantering av JavaScript-baserade element och APIer för ljudhantering.

## Ljuduppspelning

Denna laborationsuppgift är menad att introducera arbete med HTML 5s Audio-element. 

### Uppgiftsbeskrivning

Skapa en applikation som uppfyller samtliga punkter:

- **Audio-element**;  skapa ett Audio-element. Elementet kan deklareras via HTML, eller dynamiskt via JavaScript. Det är dock ett krav att elementet inte görs synligt i DOM-strukturen. Elementet kan spela upp valfritt ljudklipp.
- **Knapp**; skapa ett knapp-element. Elementet kan deklareras via HTML, eller skapas dynamiskt via JavaScript. Placera knappen i aktuell webbsidas DOM-struktur.
- **Växelknapp**; konstruera funktionalitet som använder tidigare skapad knapp som växelknapp för uppspelning. När användaren klickar på knappen, påbörjar uppspelning av ljud. Om användaren klickar på knappen när ljud spelas, då stoppas uppspelningen. Det är även lämpligt att byta etikett på knappen så att den växlar mellan `Play` och `Stop`.

### Frågeställningar

Fundera över följande frågeställningar:

- **Filformat**;  *hur är det möjligt att erbjuda samma innehåll, men i varierande filformat?*
- **Fördröjning**; *det är fullt möjligt att det uppstår en fördröjning vid uppspelning av ljudet (första gången). Detta kan resultera i en negativ användarupplevelse, finns det något sätt att lösa detta problem?*

### Resurser

Länkar till externa hjälpresurser:

- https://developer.mozilla.org/en-US/docs/Web/API/HTMLAudioElement

## Web Audio API

Denna laborationsuppgift syftar att återksapa föregående uppgift, men med Web Audio API istället för Audio-element.

### Uppgiftsbeskrivning

Skapa en applikation som uppfyller samtliga punkter:

- **Kontext**; *skapa en `AudioContext` som kan användas för ljuduppspelning.*
- **Källa**; se till att det nyskapade `AudioContext`-objektet har tillgång till en ljudkälla. Ljudfiler kan exempelvis laddas in via `XMLHttpRequest` eller via `HTMLMediaElement`.
- **Ljudvolym**; skapa en `Gain`-node i syfte att ljustera volymen under uppspelning. Notera att ljudkällan skall passera denna nod innan den når sin slutdestination.
- **Output**; se till att den manipulerade ljudkällan når sin slutdestination (enhetens högtalare).

### Frågeställningar

Fundera över följande frågeställningar:

- **Fördelar**; *på vilket sätt erbjuder detta API mer möjligheter än Audio-element?*
- **Interaktiv ljudjustering**; *undersök hurvida det är möjligt att dynamiskt ljustera ljudnivån via exempelvis range-reglage i HTML.*

### Resurser

Länkar till externa hjälpresurser:

- https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API