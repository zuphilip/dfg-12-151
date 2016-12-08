( 🚧 Work in Progress 🚧 )

Das Repositorium beinhaltet die Texte der DFG-Richtlinien "Digitalisierung" (DFG 12.151)
als Markdown-Dateien. Aktuell sind die Version von 2016 und 2013 in den entsprechenden
Forks/Branches gespeichert:

| Version | Fork/Branch | Original-PDF |
|---------|-------------|--------------|
| `12/2016` | [`2016-12`](https://github.com/zuphilip/dfg-12-151/tree/2016-12) | [DFG-Webseite](http://www.dfg.de/formulare/12_151/12_151_de.pdf) |
| `02/2013` | [`2013-02`](https://github.com/zuphilip/dfg-12-151/tree/2016-12) | [WayBackMachine](http://web.archive.org/web/20160913195655/http://www.dfg.de/formulare/12_151/12_151_de.pdf) |

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
die Unbennung als ersten Commit einzeln zu machen, so dass die restlichen Änderungen in
der Versionsgeschichte auch komfortabel in GitHub verfolgt werden können und die Änderungen
direkt im Markdown angezeigt werden.

Z. B. https://github.com/zuphilip/dfg-12-151/commit/beb9bf7ec0029797657eba7229ebad3894236600?short_path=bb7a226#diff-bb7a2265329e3e3855a69b992180a3c1


## Fehler, Korrekturvorschläge

Bei den vielen Transformationsschritten können sich auch Fehler eingeschlichen haben, 
daher sollte man im Zweifelsfall immer nochmals die Original-Dateien konsultieren.
Fehler können gerne hier gemeldet werden als [Issues](https://github.com/zuphilip/dfg-12-151/issues)
bzw. Korrekturvorschläge als [Pull Requests](https://github.com/zuphilip/dfg-12-151/pulls).


