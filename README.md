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
| [0 TOC und Vorbemerkungen](https://github.com/zuphilip/dfg-12-151/blob/2016-12/0-TOC-Vorbemerkungen.md) | :arrow_backward: [DIFF](https://github.com/zuphilip/dfg-12-151/commit/8b2939f01a0a392e81c3f7d0f7bbe9a6c7f89ba0?short_path=4cd65fa#diff-4cd65faa2464fd51cf1567ae298f3117) :arrow_forward: | [Kapitel 0](https://github.com/zuphilip/dfg-12-151/blob/2013-02/0-TOC-Vorbemerkungen.md) |
| [1 Prüfliste](https://github.com/zuphilip/dfg-12-151/blob/2016-12/1-Pruefliste.md) | :arrow_backward: [DIFF](https://github.com/zuphilip/dfg-12-151/commit/dc7524943710ec2f99046f795ab3eccada3e11a5?short_path=bb7a226#diff-bb7a2265329e3e3855a69b992180a3c1) :arrow_forward: | [Kapitel 7](https://github.com/zuphilip/dfg-12-151/blob/2013-02/7-Pruefliste.md) |
| [2 Ziele und Auswahl](https://github.com/zuphilip/dfg-12-151/blob/2016-12/2-Ziele-Auswahl.md) | :arrow_backward: [DIFF](https://github.com/zuphilip/dfg-12-151/commit/563629e262350e5d3742bcc12d2cc09f8a83bf58?short_path=63c0d40#diff-63c0d40236919f36e08f65d60a6bdc9c) :arrow_forward: | [Kapitel 1](https://github.com/zuphilip/dfg-12-151/blob/2013-02/1-Ziele-Auswahl.md) |
| [3 Digitalisierung](https://github.com/zuphilip/dfg-12-151/blob/2016-12/3-Digitalisierung.md) | :arrow_backward: [DIFF](https://github.com/zuphilip/dfg-12-151/commit/2416728e9da8fa324d07e8aa0f5473028716f9b0?diff=split#diff-775195aabd8e95314bcbe09192aaeacc) :arrow_forward: | [Kapitel 2](https://github.com/zuphilip/dfg-12-151/blob/2013-02/2-Digitalisierung.md) |
| [4 Organisatorisches](https://github.com/zuphilip/dfg-12-151/blob/2016-12/4-Organisatorisches.md) | :arrow_backward: [DIFF](https://github.com/zuphilip/dfg-12-151/commit/c663b4a2899a7324933dbaf140bd28e6c392447c?diff=split) :arrow_forward: | [Kapitel 3](https://github.com/zuphilip/dfg-12-151/blob/2013-02/3-Organisatorisches.md) |
| [5 Zitieren](https://github.com/zuphilip/dfg-12-151/blob/2016-12/5-Zitieren.md) | :arrow_backward: [DIFF](https://github.com/zuphilip/dfg-12-151/commit/f20521571c63160727bccf29cbf17e83ec46afed?short_path=ca998a7#diff-ca998a782e7b1bd2c0abf28bae7e3e7e) :arrow_forward: | [Kapitel 4](https://github.com/zuphilip/dfg-12-151/blob/2013-02/4-Zitieren.md) |
| [6 Bereitstellen](https://github.com/zuphilip/dfg-12-151/blob/2016-12/6-Bereitstellen.md) | :arrow_backward: [DIFF](https://github.com/zuphilip/dfg-12-151/commit/fec836359732ccddf7ec0e835ad3e74ff12f41fb?short_path=c681402#diff-c6814028e0725434de6bba7ee37bc405) :arrow_forward: | [Kapitel 5](https://github.com/zuphilip/dfg-12-151/blob/2013-02/5-Bereitstellen.md) |
| [7 Präsentationsstandards](https://github.com/zuphilip/dfg-12-151/blob/2016-12/7-Praesentationsstandards.md) | :arrow_backward: [DIFF](https://github.com/zuphilip/dfg-12-151/commit/c6a2ebfbf02e6f0ed0fadd36366c5ea34fe24378?short_path=8bf2548#diff-8bf25481f0789a32f91122629f95b088) :arrow_forward: | [Kapitel 6](https://github.com/zuphilip/dfg-12-151/blob/2013-02/6-Praesentationsstandards.md) |
| - |  | [Kapitel 8: Durchführung](https://github.com/zuphilip/dfg-12-151/blob/2013-02/8-Durchfuehrung.md) |
| [Anhang](https://github.com/zuphilip/dfg-12-151/blob/2016-12/Anhang.txt) | :arrow_backward: [DIFF](https://github.com/zuphilip/dfg-12-151/commit/29e87277065da3c57d1dbc59bc43771c1a9195a5?diff=split) :arrow_forward: | [Anhang](https://github.com/zuphilip/dfg-12-151/blob/2013-02/Anhang.txt) |

(Der Anhang wurde nur rudimentär bearbeitet und als normale Textdatei behandelt ohne
die ganzen Auszeichnungen in Markdown. Für einen ersten Vergleich der Version sollte dies
aber bereits genügen.)

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
