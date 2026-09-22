# Eine Vorlage auf GitHub einreichen

Du kannst deine eigenen Vorlagen hier hochladen und zur Prüfung vorschlagen. Ein GitHub-Konto genügt; direkte Schreibrechte auf das Hauptarchiv brauchst du nicht.

## 1. Vorlage prüfen und exportieren

Teste Ausschnitte, Seitenzuordnung, Format und Drehung mit einer passenden PDF. Barcodes und Pflichtangaben müssen vollständig lesbar bleiben.

Unter **Vorlagen → Community-Vorlagen → Vorlage für die Community vorbereiten** deine Vorlage auswählen und **Prüfdatei exportieren** drücken. Dieser Export entfernt eingefügte Texte und Bilder und enthält keine Original-PDF. Datumsfelder bleiben dynamisch. Verwende diesen Export statt einer privaten Vorlagensicherung. Prüfe Vorlagen- und Labelnamen selbst auf persönliche Angaben.

**Forks, hochgeladene Dateien und Pull Requests sind öffentlich.** Lade keine echten Kundenadressen, Sendungsnummern, Original-PDFs oder fremden Logos hoch. Reiche nur Vorlagen ein, deren öffentliche Weitergabe du erlauben kannst.

## 2. Datei hochladen

1. Oben auf **Fork** klicken und eine Kopie des Repositories in deinem GitHub-Konto erstellen.
2. In deinem Fork den Ordner **templates** öffnen.
3. **Add file → Upload files** auswählen und die bereinigte JSON-Datei hochladen. Einen verständlichen Dateinamen wählen, etwa `dhl-de-a4-obere-haelfte.json`.
4. Mit **Commit changes** speichern.
5. **Contribute → Open pull request** auswählen. Ziel ist `FunkyArtGFX/autopdfcut-community`, Branch `main`.

Beschreibe im Pull Request Versanddienst, Land, Art der PDF, Seitenanzahl, Position der Labels und Ausgabeformat. Beispiel: „DHL, Deutschland, Versandlabel in der oberen Hälfte einer A4-Seite, eine PDF-Seite, Ausgabe 100 × 150 mm.“

Den Katalog und die endgültige Vorlagen-ID übernimmt cz.design bei der Freigabe. Du musst `catalog.json` nicht selbst bearbeiten.

## 3. Prüfung und Freigabe

cz.design prüft deine Vorlage und stellt Rückfragen direkt im Pull Request. Erst nach Freigabe wird sie in das Hauptarchiv und den Katalog aufgenommen. Ein Upload in deinen Fork oder ein offener Pull Request ist noch keine Freigabe.

Fehler bei bestehenden Vorlagen kannst du über die **Issues** dieses Repositories mit Vorlagenname/ID und einer kurzen Beschreibung melden. Auch dort bitte keine persönlichen Daten posten.
