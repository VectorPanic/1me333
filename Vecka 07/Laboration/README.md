# Laboration - Canvas

Denna laboration innehåller ett antal övningar som relaterar till HTML 5s Canvas-element.

## Blink

Denna laborationsuppgift syftar till att skapa en mindre applikation där hela Canvas-elementet blinkar i slumpade färger, efter ett förbestämt intervall.

### Uppgiftsbeskrivning

Skapa en applikation som uppfyller samtliga punkter:

- **Canvas-element**; *skapa ett Canvas-element med valfri upplösning. Elementet kan skapas med JavaScript-kod eller deklareras som ett element i aktuell HTML-struktur.*
- **Context**; *begär en 2D-context av tidigare skapat Canvas-element.*
- **Intervall**; *skapa ett intervall som för varje sekund byter Canvas-elementets färg. Detta krav får inte lösas genom att manipulera elementets `style` eller `CSS`.* 

### Frågeställningar

Fundera över följande frågeställningar:

- **Renderingsslinga**; i denna laborationsuppgift skapades en primitiv renderingsslinga med `window.setInterval()`, prova att göra om renderingsslingan med `window.requestAnimationFrame()` istället. Hur kan slingan exekveras med ett fast intervall utan att använda `window.setInterval()`?

### Resurser

Länkar till externa hjälpresurser:

- https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/clearInterval
- https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/fillRect
- https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/fillStyle

## Linjer

Denna laborationsuppgift syftar till att skapa en mindre applikation där användare via musinteraktion, kan rita linjer till ett Canvas-element.

### Uppgiftsbeskrivning

Skapa en applikation som uppfyller samtliga punkter:

- **Canvas-element**; *skapa ett Canvas-element med valfri upplösning. Elementet kan skapas med JavaScript-kod eller deklareras som ett element i aktuell HTML-struktur.*
- **Context**; *begär en 2D-context av tidigare skapat Canvas-element.*
- **Musinterktion**; när användaren klickar på valfri position på Canvas-elementet, sparas koordinaterna för var klicket innträffade. Koordinater sparas i en list-struktur, och när listans längd blir två, drars en linje mellan koordinat ett och två. Listan innehållande koordinater töms i samband med att en linje ritas.
- **Linjer**; linjer skall ritas med varierande färg och storlek. Varje linje som ritas får en slumpad färg och tjocklek.

### Frågeställningar

Fundera över följande frågeställningar:

- **Helskärm**; är det möjligt att exekvera applikationen i helskärmsläge, alternativt ge Canvas-elementet en storlek på `100%` via CSS?

### Resurser

Länkar till externa hjälpresurser:

- https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/lineTo
- https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/moveTo
- https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/stroke
- https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/strokeStyle

