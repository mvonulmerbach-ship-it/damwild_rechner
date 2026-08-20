# damwild_rechner

Preisrechner für Damwild vom Schloss Erbach. Portionen wiegen, Gramm eintippen, Gesamtpreis und Bestellzettel bekommen. Läuft offline im Browser, ohne Server.

Live: https://mvonulmerbach-ship-it.github.io/damwild_rechner/

## Bedienung

- **Fleisch** antippen → Ziffernblock öffnet sich → Gewicht in Gramm tippen.
  - `+ Portion` erfasst das Gewicht und lässt den Block offen für das nächste Stück derselben Sorte.
  - `Fertig` übernimmt alles in die Bestellung.
- **Wurst & Gläser** antippen → jeder Tipp = 1 Stück.
- `×` in der Liste entfernt eine Portion bzw. ein Stück, beim letzten die ganze Position.
- **Zettel** erzeugt die Bestellung als Text zum Kopieren (WhatsApp) oder Drucken.
- **Zahnrad** oben rechts: Preise ändern. Sie bleiben auf dem Gerät gespeichert, `Standard` setzt sie zurück.

Bestellung und Preise liegen im localStorage des Browsers, gehen also beim Schließen nicht verloren.

## Logo

`logo.png` (Kopfzeile und Ausdruck) sowie die App-Icons sind aus dem Etiketten-Motiv „Schloss Erbach Dammwild“ erzeugt. Beim Austausch: `logo.png` 256×256 mit Transparenz, `icon-192.png` und `icon-512.png` transparent, `icon-maskable-512.png` und `apple-touch-icon.png` mit cremefarbenem Hintergrund (maskable mit 14 % Rand als Safe-Zone).

## Preise (Stand 20.08.2026)

| Artikel | Preis |
|---|---|
| Filet | 40,00 €/kg |
| Rücken, ausgelöst | 35,00 €/kg |
| Hinterkeule, ausgelöst | 25,00 €/kg |
| Vorderkeule / Schulter, ausgelöst | 20,00 €/kg |
| Nacken, ausgelöst | 17,00 €/kg |
| Haxe mit Knochen | 12,00 €/kg |
| Leberkäse fein / grob, 170 g | 4,50 €/St. |
| Lyoner, 170 g | 4,50 €/St. |
| Pfefferbeißer, 5 Stück | 7,50 €/St. |

Fleisch tiefgefroren und vakuumiert. Gläser und Pfefferbeißer nicht gefroren, trocken lagerbar.

Dauerhafte Preisänderungen gehören in `STANDARD` in der `index.html`.
