# API Gateway

## Övningar

Gör om nedanstående övningar från Lambda-modulen men där du nu använder API Gateway och varje endpoint kopplas mot en
Lambda-funktion.

**Todo API**

Gör ett enkelt todo api i en Lambda-funktion där man kan hämta, spara, uppdatera och ta bort todos. I och med att lambda-funktioner inte kan dela variabler så får varje lambda-funktion ha en egen todo-variabel.

**Krypteringsalgoritm**

Gör två endpoints den ena är `/encrypt` och den andra `/decrypt`. I `/encrypt` så skickar man in en text som sedan krypteras på något egenpåhittat sätt (ex. Ceasar chiffer) och retunerar den krypterade texten och `/decrypt` tar emot den krypterade texten och returnerar den dekrypterade texten.

Snyggast krypteringsalgoritm vinner!
