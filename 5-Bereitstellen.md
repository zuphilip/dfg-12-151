# Bereitstellung der Digitalisate für die Öffentlichkeit 

## Rechteklärung und Open Access 

Die Deutsche Forschungsgemeinschaft ist Mitunterzeichnerin der „Berlin Declaration“ zum open access.
Die Ergebnisse der durch sie geförderten Digitalisierungsprojekte stehen der weltweiten Forschung daher unentgeltlich und im Geiste dieser Erklärung zur Verfügung. [49] 
Insofern wird grundsätzlich davon ausgegangen, dass Digitalisate in einer Qualität, die die Verfolgung der großen Mehrzahl der üblichen Forschungszwecke erlaubt, kostenfrei über das Internet bereitgestellt werden.
Sollte in Projekten davon abgewichen werden, ist dies im Antrag ausdrücklich zu begründen. 

Die Digitalisierung von wissenschaftlichen Materialien wird durch die DFG gefördert, um diese Materialien der Forschung in Deutschland und weltweit zugänglich zu machen.
Alle Projekte sind also so anzulegen, dass die Ergebnisse der Forschung frühzeitig und nachhaltig zugänglich werden.
Dies wird in nahezu allen Fällen die Bereitstellung der Digitalisate im Internet einschließen. 

Bereits mit Beginn der Projektplanung, spätestens aber zum Zeitpunkt der Antragstellung muss eine Rechteklärung bezüglich der zu digitalisierenden Materialien erfolgt sein. 
Insbesondere eventuell vorliegende Urheber-, Persönlichkeits- und Leistungsschutzrechte müssen dabei berücksichtigt werden.
Die Rechteklärung gestaltet sich häufig aufwendiger als zunächst erwartet.
Für die entsprechenden Aufwände ist daher ausreichend Zeit und personeller Einsatz einzuplanen.
Stellt sich die Rechteklärung als schwierig dar, wird empfohlen, professionelle Unterstützung, beispielsweise durch das Justiziariat der bestandshaltenden Einrichtung zu suchen.
 
Im Sinne des open access und der open source [50] wird erwartet, dass alle Metadaten 
(deskriptive und strukturelle) und maschinenlesbaren Volltexte bzw. das den Volltexten zu Grunde liegende XML sowie XSLT-Skripte und DTDs oder XML-Schema-Dateien unter einer Creative Commons-Lizenz angeboten werden.
Maßgebliches Ziel ist es, Möglichkeiten zu schaffen, Metadaten und Volltexte auch in anderen Nutzungskontexten als der unmittelbaren Projektumgebung (z.B. zum Zwecke des data mining oder der Datenaggregation z.B. im ZVDD) auswerten zu können; dies erfordert das Herunterladen, die Neuindexierung und das Anbieten in eigenen Forschungs- und Präsentationskontexten.
Um die Leistung des Urhebers angemessen zu würdigen, wird empfohlen diese Texte unter einer CC BY-SA-Lizenz zur Verfügung zu stellen.
Bei Metadaten ist zu prüfen, ob sie unter einer CC0-Lizenz zur Verfügung gestellt werden können. 

Darüber hinaus sollten Images in einer Form bereitgestellt werden, die eine vollumfängliche wissenschaftliche Nachnutzung in anderen Forschungskontexten erlaubt (z.B. durch Nutzung von einzelnen Images „in Frames“ nach dem Modell des DFG-Viewers bzw. Googles iFrame-Einbettung oder durch generelle Erteilung einer Erlaubnis, Vorschaubilder auf fremden Servern anzeigen zu dürfen).
Die Erhebung von Reproduktionsgebühren oder Entgelten für Kopien in darüber hinausgehenden Qualitäten, Derivaten oder für die Herstellung anderer Medienformen (CD, Druck, etc.) bleibt davon unberührt. 

Die DFG erwartet, dass DFG-geförderte Projekte auf ihren im Internet angebotenen Daten eindeutige Herkunftsnachweise sowie gegebenenfalls den Hinweis auf die Förderung durch die DFG anbringen.
Dies erfolgt im Fall von Bilddigitalisaten in der Regel durch das Hinzurechnen einer Nachweisleiste in die veröffentlichte Nutzerkopie (zum Beispiel im Grafikformat JPEG).
Im Fall von Volltexten geschieht der Nachweis durch entsprechende Hinweise im Header der Textdatei, ebenso können die Nachweise in die Bildheader eingebettet werden.
In jedem Fall aber muss die Herkunftsangabe in den begleitenden Metadaten enthalten sein und im Bereitstellungssystem auch ausgegeben werden. 

Bei Projekten, in denen nicht nur gemeinfreie Materialien digitalisiert werden und daher mit kommerziellen Partnern oder Verlagen zusammengearbeitet wird, kann eine verzögerte Publikation (moving wall) von bis zu einem Jahr nach Projektende vereinbart werden. 


[49] http://oa.mpg.de/openaccess-berlin/berlindeclaration.html  
[50] Vgl. Bodard, Gabriel/Juan Garcės: Open Source Critical Editions: A Rationale, in: Marilyn Deegan/Kathryn Sutherland (Hrsg.): 
Text editing, print and the digital world., Farnham: Ashton Publishing 2009, S.83-98. 


### Mindestanforderungen für die Bereitstellungssysteme von Digitalisaten 

#### Funktionalitätsanforderungen 

Unabhängig von der gewählten Architektur müssen mindestens folgende Funktionalitäten bereitgestellt werden: 

Sammlungen/Bestände sind in der Regel über eine Vielzahl von Wegen zugänglich: 

* über die Website der anbietenden Institution 
* über eine OAI-Schnittstelle 
* über den lokal implementierten oder an einem anderen Ort betriebenen „DFG-Viewer“, sofern für das angebotene Material zutreffend (vgl. Kapitel 6.3) 
* über eine Suchanfrage an den lokalen und regionalen Bibliothekskatalog/an die jeweilige materialspezifische Online-Anwendung 
* sofern vorhanden über eines der von der DFG geförderten materialspezifischen Portale, die einen integrierten Zugriff auf alle im DFG-Programm geförderten digitalen Sammlungen ermöglichen, bzw. ein gemeinsames Portal der „Virtuellen Fachbibliotheken“ 
* über Internet-Suchmaschinen. 

Über die genannte OAI-Funktionalität ist auch der DFG-Viewer zu bedienen (sofern das jeweilige Format unterstützt wird). 
Eine Ablieferung lediglich durch XML-Dateien sollte zugunsten der OAI- Funktionalitäten nicht mehr erfolgen. 
Neu eingerichtete OAI-Schnittstellen sollten in Frage kommenden Portalen und Fachbibliotheken gemeldet werden. 
Ferner sollten geeignete Maßnahmen ergriffen werden, die dazu führen, dass die Metadaten von Suchmaschinen gefunden werden (z.B. mit dem sitemap protocol [51]). 

Den Nutzerinnen und Nutzern sollte neben dem gezielten Zugriff auf spezifizierte Dokumente 
über eine Recherche in Metadaten (searching) auch die Möglichkeit geboten werden, in vorab definierten Sammlungen, Sammlungsteilen oder Beständen strukturiert zu navigieren 
(browsing).
Bei der Suche ist darauf zu achten, dass im Zweifelsfall einfache, googleorientierte Suchinstrumente einer größeren Benutzergemeinschaft dienen als stark gefelderte Suchmasken, die ein eingehendes Verständnis der Datenstruktur der jeweiligen Sammlung oder des jeweiligen Bestands erfordern.
Idealerweise werden beide Aspekte durch die Facettierung der Suche kombiniert, bei der die Nutzerinnen und Nutzer Möglichkeiten an die Hand bekommen, selbst größere Treffermengen nach definierten Kriterien (Facetten) zu reduzieren.
Darüber hinaus bleibt auch die differenzierte, stark gefelderte Suche als zusätzliches Hilfsmittel für eine hochspezialisierte Fachcommunity ein wünschenswertes Angebot. 

Außerdem sind folgende Funktionen zu implementieren: 

* Downloadfunktion [52] 
* Druckfunktion für die ausgegebene Dokumentansicht [53] 
* Aus zentralen DFG-geförderten Informationssystemen (VD16, VD17, VD18, 
Fachportalen etc.) sollte zuerst auf eine Ansicht im Style „DFG-Viewer“ verlinkt werden. 
* Für sämtliche DFG-geförderten Bereitstellungssysteme wird erwartet, dass Nutzerinnen und Nutzer die automatisierte Möglichkeit zum Feedback bezüglich des digitalen Angebots erhalten.
Eine entsprechende Möglichkeit ist auf der Projektseite bzw. im digitalen Bereitstellungssystem an zentraler Stelle einzurichten. 


#### Technische Mindestanforderungen 

Server sind so anzulegen, dass sie, soweit anwendbar [54], 

* alle Materialien in einer hinreichend guten Qualität anbieten, so dass die Benutzung zu wissenschaftlichen Zwecken auf an den Hochschulen üblicherweise vorhandenem Equipment mühelos möglich ist.
Dies wird beispielsweise dadurch erreicht, dass Schrift in einer Größe angeboten wird, die problemlos gelesen werden kann. 
* alle Materialien aber auch in einer Qualität anbieten, die über DSL-Anschlüsse ohne unzumutbare Verzögerungen bearbeitbar sind. 
* zum wissenschaftlichen Gebrauch den kostenlosen Download kompletter Einheiten in einer einzigen Datei (beispielsweise einzelne gedruckte Werke) ermöglichen. 
* alle jeweils gängigen Browser unterstützen, soweit dies der Natur der Sache nach nicht unmöglich ist. [55] 


[51] http://www.sitemaps.org/  
[52] Ein Download nach Abschnitten oder einzelnen Seiten ist dann vorzusehen, wenn die Größe der Gesamtdatei nicht mehr handhabbar wäre.  
[53] Eine Druckfunktion nach Abschnitten oder einzelnen Seiten ist dann vorzusehen, wenn die Größe der Gesamtdatei nicht mehr handhabbar wäre.  
[54] Hier wird nachdrücklich das Kriterium der Alltagstauglichkeit gefordert, es geht nicht um die Realisierung abstrakter Wünschbarkeiten.
Können Objekte eines Projekts ihrer Natur nach auf Bildschirmen mit einer Auflösung unter 1600 x 1200 nicht sinnvoll dargestellt werden, wird kein Aufwand für Scheinlösungen gefordert; ist ein Objekt unter 3 MB nicht sinnvoll bearbeitbar, verletzt es das Kriterium der DSL-Tauglichkeit des Servers nicht, wenn kein Angebot kleinerer Versionen erfolgt. 
[55] Wird ein für eine fortgeschrittene 3D-Anwendung notwendiges Format von einem Browser nicht unterstützt, ist es nicht erforderlich den Aufwand zu betreiben, ein geeignetes Plugin zu entwickeln. 