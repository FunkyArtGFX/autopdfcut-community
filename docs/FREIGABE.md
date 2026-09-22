# Prüfung und Freigabe · cz.design

1. Anhänge außerhalb des öffentlichen Repositories ablegen. Keine E-Mail-Verläufe, Absenderadressen oder Original-PDFs committen.
2. JSON mit AutoPDFCut importieren und auf gültigen Aufbau prüfen. Keine mitgelieferten Skripte ausführen.
3. Namen und Ergänzungen auf persönliche Angaben prüfen, Bilder entfernen und Zustimmung zur öffentlichen Weitergabe klären. Nur neutrale Layoutinformationen, Druckeinstellungen und gegebenenfalls dynamische Datumsfelder veröffentlichen.
4. Zuschnitte, Seitenzuordnung, Format, Drehung und Ergänzungen mit geeigneten anonymisierten Testdaten prüfen. Kompatibilität nur für den beschriebenen Dokumentaufbau angeben.
5. Stabile ID mit Präfix `community-` vergeben, etwa `community-dhl-de-a4-top-v1`. Kurze sachliche Beschreibung ergänzen.
6. Freigegebene Vorlage unter `templates/<id>.json` ablegen. In `catalog.json` einen Eintrag mit `template` (vollständige Definition) und `description` ergänzen. Datei und Katalog müssen dieselbe Definition enthalten.
7. Nur diese geprüften Dateien in `main` veröffentlichen. Eine E-Mail allein veröffentlicht nichts.

Fehlerhafte Vorlagen im Katalog korrigieren oder entfernen. Bereits importierte lokale Kopien werden dadurch nicht automatisch verändert oder gelöscht. Nutzer können die korrigierte Fassung erneut importieren.

## Katalogformat

`catalog.json` enthält `version: 1` und `templates: []`. Jeder Eintrag hat `template` und `description`. Die Definition entspricht dem AutoPDFCut-Format mit `version`, `id`, `name`, `createdAt`, `pages` und `cuts`.

`pages` enthält Seitenmaße und neutrale Erkennungsmerkmale; `cuts` die Ausschnitte, Ausgabeformate, Labeltypen, Druckeinstellungen und bereinigten Ergänzungen. Original-PDFs gehören nie in den Katalog.
