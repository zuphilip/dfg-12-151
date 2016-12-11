( 🚧 Work in Progress 🚧 )

Das Repositorium beinhaltet die Texte der DFG-Richtlinien "Digitalisierung" (DFG 12.151)
als Markdown-Dateien. Aktuell sind die Version von 2016 und 2013 in den entsprechenden
Forks/Branches gespeichert:

| Fork/Branch | Beschreibung | Original-PDF | Version |
|---------|---|-------------|--------------|
| [`2016-12`](https://github.com/zuphilip/dfg-12-151/tree/2016-12) | Die aktuelle Version von 2016-12 der DFG-Richtlinie in Markdown aufbauend auf der vorherigen Version. | [DFG-Webseite](http://www.dfg.de/formulare/12_151/12_151_de.pdf) | `12/2016` |
| [`2013-02`](https://github.com/zuphilip/dfg-12-151/tree/2013-02) | Die vorletzte Version von 2013-02 der DFG-Richtlinie in Markdown. Dieser Branch wird auch jeweils als Grundlage für die neuere Version genutzt (`git rebase`). | [WayBackMachine](http://web.archive.org/web/20160913195655/http://www.dfg.de/formulare/12_151/12_151_de.pdf) | `02/2013` |
| [master](https://github.com/zuphilip/dfg-12-151) | Hier befindet sich nur diese README-Datei. | |

Das Ziel hier ist auch, die Unterschiede zwischen den verschiedenen Versionen relativ
komfortabel aufzuzeigen.

Die gesamten Richtlinien (ca. 80 Seiten) sind in verschiedene `.md`-Dateien entsprechend den
verschiedenen Kapiteln aufgeteilt worden. Die Markup-Version hier ist aus der PDF-Version
durch Extrahieren des Textes, Suchen und Ersetzungen sowie viel händischer Nacharbeit erfolgt.

## Unterschiede anzeigen

Man kann insgesamt die Branches miteinander vergleichen (TODO follow renames):

```sh
git diff --word-diff=plain 2016-12..2013-02
```

bzw. direkt in GitHub https://github.com/zuphilip/dfg-12-151/compare/2013-02...2016-12

Die Umsortierung der Abschnitte und daraus Unbenennungen über der Dateien (`git mv`) macht
das Nachvollziehen der Änderungen teilweise etwas schwieriger. Daher wird bewusst versucht
die Unbennung als ersten Commit einzeln zu machen und die gesamten restlichen Änderungen einer
Datei in genau einem Commit, welcher dann auch schön die Änderungen über `git diff <commit>`
enthält.

|Kapitel in der 2016er Version| DIFF | zugehöriges Kapitel der 2013 Version|
|---|---|---|
| [0 TOC und Vorbemerkungen](https://github.com/zuphilip/dfg-12-151/blob/2016-12/0-TOC-Vorbemerkungen.md) | :arrow_backward: [DIFF](https://github.com/zuphilip/dfg-12-151/commit/d9f23a2e5620c0eee11fa97676540d4bb7d96ea5?short_path=4cd65fa#diff-4cd65faa2464fd51cf1567ae298f3117) :arrow_forward: | [Kapitel 0](https://github.com/zuphilip/dfg-12-151/blob/2013-02/0-TOC-Vorbemerkungen.md) |
| [1 Prüfliste](https://github.com/zuphilip/dfg-12-151/blob/2016-12/1-Pruefliste.md) | :arrow_backward: [DIFF](https://github.com/zuphilip/dfg-12-151/commit/decc5a99cda33a015f3abed2675ef205d884dc87?short_path=bb7a226#diff-bb7a2265329e3e3855a69b992180a3c1) :arrow_forward: | [Kapitel 7](https://github.com/zuphilip/dfg-12-151/blob/2013-02/7-Pruefliste.md) |
| [2 Ziele und Auswahl](https://github.com/zuphilip/dfg-12-151/blob/2016-12/2-Ziele-Auswahl.md) | :arrow_backward: [DIFF](https://github.com/zuphilip/dfg-12-151/commit/20643f89bf0f970c16e14cee26f517b94ae1180a?short_path=63c0d40#diff-63c0d40236919f36e08f65d60a6bdc9c) :arrow_forward: | [Kapitel 1](https://github.com/zuphilip/dfg-12-151/blob/2013-02/1-Ziele-Auswahl.md) |
| [3 Digitalisierung](https://github.com/zuphilip/dfg-12-151/blob/2016-12/3-Digitalisierung.md) | :arrow_backward: [DIFF](https://github.com/zuphilip/dfg-12-151/commit/2d1aeebe092efe5974f8b9fd30a145a5e495c096?diff=split#diff-775195aabd8e95314bcbe09192aaeacc) :arrow_forward: | [Kapitel 2](https://github.com/zuphilip/dfg-12-151/blob/2013-02/2-Digitalisierung.md) |
| [4 Organisatorisches](https://github.com/zuphilip/dfg-12-151/blob/2016-12/4-Organisatorisches.md) | :arrow_backward: [DIFF](https://github.com/zuphilip/dfg-12-151/commit/d1971c26f600d6218f02eb696f555eca8a873453?diff=split#diff-04ff1abe37ccd15f4d5060fdd23b6280) :arrow_forward: | [Kapitel 3](https://github.com/zuphilip/dfg-12-151/blob/2013-02/3-Organisatorisches.md) |

(weitere Kapitel folgen noch)

## Fehler, Korrekturvorschläge

Bei den vielen Transformationsschritten können sich auch Fehler eingeschlichen haben, 
daher sollte man im Zweifelsfall immer nochmals die Original-Dateien konsultieren.
Fehler können gerne hier gemeldet werden als [Issues](https://github.com/zuphilip/dfg-12-151/issues)
bzw. Korrekturvorschläge als [Pull Requests](https://github.com/zuphilip/dfg-12-151/pulls).

## Copyright

Für den gesamten Text der Richtlinien in den verschiedenen Versionen "liegen Copyright 
und alle weiteren Rechte bei der Deutschen Forschungsgemeinschaft. Die Weiterverbreitung,
auch in Auszügen, für pädagogische, wissenschaftliche oder private Zwecke ist unter Angabe
der Quelle gestattet (sofern nichts anderes an der entsprechenden Stelle ausdrücklich angegeben
ist). Eine Verwendung im gewerblichen Bereich bedarf der Genehmigung durch die Deutsche 
Forschungsgemeinschaft." Vgl. http://www.dfg.de/service/kontakt_impressum/impressum/#micro267425
