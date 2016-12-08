( 🚧 Work in Progress 🚧 )

Das Repositorium beinhaltet die Texte der DFG-Richtlinien "Digitalisierung" (DFG 12.151)
als Markdown-Dateien. Aktuell sind die Version von 2016 und 2013 in den entsprechenden
Forks/Branches gespeichert:

| Version | Fork/Branch | Original-PDF |
|---------|-------------|--------------|
| `12/2016` | [`2016-12`](https://github.com/zuphilip/dfg-12-151/tree/2016-12) | [DFG-Webseite](http://www.dfg.de/formulare/12_151/12_151_de.pdf) |
| `02/2013` | [`2013-02`](https://github.com/zuphilip/dfg-12-151/tree/2013-02) | [WayBackMachine](http://web.archive.org/web/20160913195655/http://www.dfg.de/formulare/12_151/12_151_de.pdf) |

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
| [0 TOC und Vorbemerkungen](https://github.com/zuphilip/dfg-12-151/blob/2016-12/0-TOC-Vorbemerkungen.md) | :arrow_backward: [DIFF](https://github.com/zuphilip/dfg-12-151/commit/6b6d0617be3a200bc4ca6bbe4b4a757615e92faa?short_path=4cd65fa#diff-4cd65faa2464fd51cf1567ae298f3117) :arrow_forward: | [Kapitel 0](https://github.com/zuphilip/dfg-12-151/blob/2013-02/0-TOC-Vorbemerkungen.md) |
| [1 Prüfliste](https://github.com/zuphilip/dfg-12-151/blob/2016-12/1-Pruefliste.md) | :arrow_backward: [DIFF](https://github.com/zuphilip/dfg-12-151/commit/96a728cedf59bf19e9e904c3f32027698afc7fb0?short_path=bb7a226#diff-bb7a2265329e3e3855a69b992180a3c1) :arrow_forward: | [Kapitel 7](https://github.com/zuphilip/dfg-12-151/blob/2013-02/7-Pruefliste.md) |
| [2 Ziele und Auswahl](https://github.com/zuphilip/dfg-12-151/blob/2016-12/2-Ziele-Auswahl.md) | :arrow_backward: [DIFF](https://github.com/zuphilip/dfg-12-151/commit/1fdd6fa92bd0da621634abb724afabbe3df094ab?short_path=63c0d40#diff-63c0d40236919f36e08f65d60a6bdc9c) :arrow_forward: | [Kapitel 1](https://github.com/zuphilip/dfg-12-151/blob/2013-02/1-Ziele-Auswahl.md) |

(weitere Kapitel folgen noch)

## Fehler, Korrekturvorschläge

Bei den vielen Transformationsschritten können sich auch Fehler eingeschlichen haben, 
daher sollte man im Zweifelsfall immer nochmals die Original-Dateien konsultieren.
Fehler können gerne hier gemeldet werden als [Issues](https://github.com/zuphilip/dfg-12-151/issues)
bzw. Korrekturvorschläge als [Pull Requests](https://github.com/zuphilip/dfg-12-151/pulls).


