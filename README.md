# AutoPDFCut · Community-Vorlagen

**Einmal zuschneiden. Als Vorlage speichern. Wiederholt und im Stapel drucken.**

Dieses öffentliche Archiv gehört zu **AutoPDFCut von cz.design**. Hier sammeln wir geprüfte Zuschnittvorlagen für Versandlabels, Zollformulare, Belege und andere PDF-Ausschnitte. Die App wird separat über die Stores vertrieben; dieses Repository enthält Vorlagen und Anleitungen.

## AutoPDFCut herunterladen

| Plattform | Store-Eintrag |
| --- | --- |
| Windows | [AutoPDFCut im Microsoft Store](https://apps.microsoft.com/detail/9NTBF8ZLWJ0D) |
| Android | [AutoPDFCut bei Google Play](https://play.google.com/store/apps/details?id=czfa.autocut) |

Die Verfügbarkeit richtet sich nach Land und Freigabestatus im jeweiligen Store. Weitere Plattformen ergänzen wir, sobald ein öffentlicher Eintrag vorliegt.

[Website & Support](https://www.easyepr.com/autopdfcut/) · [Impressum](https://www.easyepr.com/autopdfcut/impressum/) · [Bedienhilfe](docs/HILFE.md) · [Vorlage einreichen](CONTRIBUTING.md)

## Was macht eine Vorlage?

Eine Vorlage beschreibt, **welche Bereiche welcher PDF-Seiten** ausgeschnitten werden und wie groß und gedreht sie ausgegeben werden. Sie kann Druckeinstellungen und neutrale Ergänzungsfelder enthalten. Sie enthält keine Original-PDF und kauft oder erzeugt keine Frankierung.

Beispiel: Ein Versandlabel liegt immer in der oberen Hälfte einer A4-Seite. Du markierst den Bereich einmal, wählst 100 × 150 mm als Ausgabeformat und speicherst die Vorlage. PDFs mit demselben Aufbau kannst du danach einzeln oder gemeinsam verarbeiten.

Vorlagen gehören zu einem **bestimmten Dokumentaufbau**, nicht pauschal zu einem Versanddienst. Ein anderer DHL-, Hermes- oder UPS-PDF-Aufbau kann eine andere Vorlage benötigen.

## Vorlagen verwenden

1. Eine freigegebene JSON-Datei aus [templates](templates/) herunterladen.
2. In AutoPDFCut unter **Vorlagen → Importieren** übernehmen.
3. Auf der Startseite die Vorlage mit der PDF-Ablage verbinden.
4. Passende PDFs ablegen, die Vorschau prüfen und drucken oder als PDF speichern.

Nach dem Import bleibt die Vorlage auf deinem Gerät und lässt sich offline verwenden. Das Archiv ist für die Online-Suche vorgesehen; bis die jeweilige App-Version angebunden ist, funktioniert der manuelle Import. Der Katalog startet leer und wächst mit den geprüften Einreichungen.

## Deine Vorlage beisteuern

Du kannst deine Vorlage direkt auf GitHub **per Pull Request** beisteuern: Repository forken, die bereinigte JSON-Datei unter `templates/` hochladen und einen Pull Request öffnen.

In der App unter **Community-Vorlagen → Vorlage für die Community vorbereiten** die bereinigte Prüfdatei exportieren. Original-PDFs, eingefügte Texte und Bilder werden dabei nicht mitgegeben. Prüfe auch Vorlagen- und Labelnamen auf persönliche Angaben: Forks und Pull Requests sind öffentlich sichtbar.

Beschreibe Versanddienst, Land, Dokumentaufbau und Ausgabeformat. **cz.design prüft jede Einreichung. Erst nach Freigabe und Zusammenführen erscheint sie im Katalog.**

[Ausführlicher Einreichungsablauf](CONTRIBUTING.md)

## Hilfe in der App

Der **Hilfe-Button** öffnet eine Tour mit Hervorhebung der wichtigen Elemente der jeweiligen Ansicht. Die [Bedienhilfe](docs/HILFE.md) erklärt Zuschnitt, Seitenwechsel, Text/Datum/Logo, Stapelverarbeitung, Drucken und die optionalen Tools **Adress Check** und **Versandkosten**.

**Einstellungen** enthalten Sprache, Hell-/Dunkelmodus, Version, Support, Impressum und Credits. Die verfügbaren Funktionen hängen von der installierten App-Version ab.

## Inhalt des Archivs

- `templates/`: ausschließlich freigegebene Vorlagendateien.
- `catalog.json`: maschinenlesbarer Katalog; anfangs leer.
- `docs/HILFE.md`: Bedienhilfe und Zuordnung der Vorlagen zur App.
- `docs/FREIGABE.md`: Prüfung und Veröffentlichung durch cz.design.

## English

This is the public template library for **AutoPDFCut by cz.design**. Templates describe PDF crop areas and print settings; they do not contain original PDFs or purchase postage. Import an approved JSON template into AutoPDFCut, then use it offline with PDFs sharing the same layout. Store links are listed above. Submissions are reviewed by cz.design before publication. To contribute, fork this repository, upload a sanitized JSON file under `templates/`, and open a pull request. Describe the document layout and output format. Forks and pull requests are public: remove personal data before uploading.

Powered by [EasyEPR.com](https://www.easyepr.com/)
