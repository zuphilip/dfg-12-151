( 🚧 Work in Progress 🚧 )

Das Repositorium beinhaltet eine Kopie der DFG-Richtlinien "Digitalisierung" (DFG 12.151)
als Markdown-Dateien. Zusätzlich werden die unterschiedlichen Versionen in den entsprechenden
Forks/Branches gespeichert (aktuell die 2016er und 2013er Version), so dass man auch relativ
komfortabel die Unterschiede zwischen den Versionen sehen kann.

Die gesamten Richtlinien (ca. 80 Seiten) sind in verschiedene `.md`-Dateien entsprechend den
verschiedenen Kapiteln aufgeteilt worden. Die Markup-Version hier ist aus der PDF-Version
durch Extrahieren des Textes, Suchen und Ersetzungen sowie viel händischer Nacharbeit erfolgt.

Der Branch `2016-12` baut auf dem Branch `2013-02` auf und somit kann man die beiden Versionen
der DFG-Richtlinien miteinander vergleichen, indem man die beiden Branches vergleicht.
Alternativ kann man für die verschiedenen Dateien die Versionsgeschichte nachvollziehen.

## Unterschiede anzeigen

Man kann insgesamt die Branches miteinander vergleichen (TODO follow renames):

```sh
git diff --word-diff=plain 2016-12..2013-02
```

bzw. direkt in GitHub https://github.com/zuphilip/dfg-12-151/compare/2013-02...2016-12

Die Umsortierung der Abschnitte und daraus Unbenennungen über der Dateien (`git mv`) macht
das Nachvollziehen der Änderungen teilweise etwas schwieriger. Daher wird bewusst versucht
die Unbennung als ersten Commit einzeln zu machen, so dass die restlichen Änderungen in
der Versionsgeschichte auch komfortabel in GitHub verfolgt werden können und die Änderungen
direkt im Markdown angezeigt werden.

Z. B. https://github.com/zuphilip/dfg-12-151/commit/beb9bf7ec0029797657eba7229ebad3894236600?short_path=bb7a226#diff-bb7a2265329e3e3855a69b992180a3c1


## Original-Dateien

* 2016-12: http://www.dfg.de/formulare/12_151/12_151_de.pdf
* 2013-02: http://web.archive.org/web/20160913195655/http://www.dfg.de/formulare/12_151/12_151_de.pdf

Weitere Versionen findet man unter http://web.archive.org/web/*/http://www.dfg.de/formulare/12_151/12_151_de.pdf

## Fehler, Korrekturvorschläge

Bei den vielen Transformationsschritten können sich auch Fehler eingeschlichen haben, 
daher sollte man im Zweifelsfall immer nochmals die Original-Dateien konsultieren.
Fehler können gerne hier gemeldet werden als [Issues](https://github.com/zuphilip/dfg-12-151/issues)
bzw. Korrekturvorschläge als [Pull Requests](https://github.com/zuphilip/dfg-12-151/pulls).


