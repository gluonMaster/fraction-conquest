# Fraction Conquest (Bruch-Eroberung)

**[▶ Im Browser spielen](https://gluonmaster.github.io/fraction-conquest/)** · [English](README.md) · [Русский](README.ru.md)

Ein Lernspiel zum Bruchrechnen für die Klassen 5 bis 7 (11 bis 13 Jahre). Jede richtige Antwort erobert ein Gebiet auf der Karte, jede falsche kostet eins, sodass aus einer Übungsrunde ein kleines Strategiespiel wird. Lehrkräfte und Eltern stellen Themen und Schwierigkeit ein. Das Spiel läuft im Browser, auf Deutsch oder Russisch, ohne Installation und ohne Konto.

![Bruchaufgabe neben der Gebietskarte](docs/screenshots/game.png)

## Funktionen

- 11 Themen: Kürzen, gemischte Zahlen, gemeinsamer Nenner, die vier Grundrechenarten, Umwandlung zwischen Brüchen und Dezimalzahlen sowie kombinierte Aufgaben.
- 4 Schwierigkeitsstufen.
- Sofortige Rückmeldung mit einer Erklärung nach jeder falschen Antwort.
- Einstellungsseite ([admin.html](admin.html)) für Themen, Schwierigkeit und Timer.
- Testseite ([test.html](test.html)), die die Mathe-Engine im Browser prüft.
- Reines HTML, CSS und JavaScript, ohne Frameworks und Build-Schritt.

## Steuerung

- Auf eine der sechs Antworten klicken oder `1` bis `6` drücken.
- Nach einer falschen Antwort die Erklärung lesen und mit der nächsten Aufgabe weitermachen.

## Lokal starten

Repository herunterladen oder klonen und `index.html` im Browser öffnen. Über einen lokalen Server verhält sich das Spiel wie die Online-Version:

```bash
python -m http.server 8000
```

Danach `http://localhost:8000/index.html` öffnen (oder `admin.html`, `test.html`). Das Spiel ist für Bildschirme ab 1024×768 in aktuellen Versionen von Chrome, Firefox und Edge gedacht. Einstellungen und Fortschritt werden im `localStorage` des Browsers gespeichert.

## Autor und Lizenz

Entwickelt von Dr. Konstantin S. Shakun mit Unterstützung von KI-Coding-Agenten. Der Code steht unter der [MIT-Lizenz](LICENSE).
