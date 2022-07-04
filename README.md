# DOM-Segment-3

Jetzt wollen wir Eingaben aus einem Formular verarbeiten und dem Nutzer ein Ergebnis mitteilen.

## Aufbau
Wir benötigen eine `index.html`, eine `style.css` und eine `index.js`.

Verbinde die Dateien miteinander wie in der letzten Übung.

Diesmal wirst du auch das CSS Stylesheet brauchen (oder SASS wem das lieb ist).

## Formular
Arbeite nun an deinem Formular.

Mit dem Formular kann ein Anwender seine Einkünfte aus Arbeit, Vermietung&Verpachtung und aus Gewinnspielen eintragen.

Am Ende wird ihm die Summe seiner Einkünfte errechnet und angezeigt.

Es gibt folgende Eingabefelder:
* Einkünfte aus Arbeit (Zahl, Minimum: 0, optional).
* Einkünfte aus Vermietung&Verpachtung (Zahl, Minimum: 0, optional).
* Einkünfte aus Gewinnspielen (kann negativ sein, Zahl, optional).

Dein Formular braucht noch einen Submit Button

## Style
Zentriere dein Formular in der Mitte des Bildschirmes

Benutze dazu die Flexbox.

## JavaScript
Deine JavaScript soll die Funktion `run()` verfügen.

Verknüpfe sie im Formular unter `action` mit dem Wert `javascript:run()`.

Speichere in der Funktion nun die Eingaben aus den Formularfeldern in einzelnen Konstanten ab.

Berechne zuletzt die Summe und gebe sie in einem `alert` an den Anwender aus.
