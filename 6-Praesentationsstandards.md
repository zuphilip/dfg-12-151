## Präsentationsstandards für Textwerke, DFG-Viewer 

Die oben angesprochenen Grundsätze gelten für alle Arten von Projekten, die digitale Inhalte bereitstellen.
Bei der Bereitstellung von Digitalisaten, die den Charakter von digitalen Büchern oder Dokumenten haben, gelten zusätzlich folgende Mindestanforderungen.
Diese betreffen einige Basisanforderungen und die mindestens zu realisierende Funktionalität. 


### Basisanforderungen und Architektur 

Das Bereitstellungssystem verknüpft die digitalisierten Bild- oder Volltextdateien zu einer Dokumentstruktur, um für die Nutzerinnen und Nutzer eine Navigation innerhalb des Dokumentes zu ermöglichen.
Weiterhin stellt es Verbindungen zwischen digitalen Dokumenten bzw. Teilen davon (z.B. Kapitel, Seiten) und Metadaten her, um den Nutzerinnen und Nutzern, ausgehend von einer Recherche in Metadatenbeständen, den Zugriff auf das einzelne Dokument oder auf bestimmte Dokumentteile zu ermöglichen.
Schließlich organisiert es digitale Dokumente zu sachlich oder durch Provenienz zusammengehörigen digitalen Sammlungen bzw. Beständen, um den Nutzerinnen und Nutzern die Navigation zwischen Dokumenten und Sammlungen analog zu einer Freihandbibliothek in sachlicher Aufstellung zu bieten.
Es stellt entsprechende Benutzeroberflächen für Recherche, Navigation, Zugriff und Abruf von Metadaten, Dokumenten, Sammlungen und Beständen zur Verfügung und unterstützt den weitgehend automatisierten Ex- und Import von standardkonformen Rohdaten. 
Die Bereitstellungssysteme der einzelnen Bibliotheken und Archive sollten sowohl bei der Navigation in digitalen Sammlungen/Beständen als auch bei der Recherche über Indizes und Register einen institutionenübergreifenden Zugriff ermöglichen.
Darüber hinaus ist eine transparente Verknüpfung der Bereitstellungssysteme mit lokalen Katalogsystemen und Verbunddatenbanken wünschenswert. 

Zur Lösung dieser Aufgaben können unterschiedliche Systemarchitekturen eingesetzt werden. 
Folgende grundlegende Alternativen sind denkbar: 

* Die Metadaten werden zentral in einem Katalogsystem (z. B. dem lokalen OPAC oder einem Bibliotheksverbundkatalog) gehalten, die digitalen Dokumentdateien (inkl. elektronischem Inhaltsverzeichnis und Register) werden in einem hierarchisch gegliederten Dateisystem auf einem gesonderten Dokumentenserver für den Online-Zugriff bereitgestellt.
Die Struktur der digitalisierten Sammlung bzw. die interne Struktur der digitalisierten Dokumente kann dabei durch die Hierarchie des Dateisystems abgebildet werden. 
* Ein Dokumenten-Management-System (DMS) oder Content-Management-System (CMS) kommt zum Einsatz. 


### Funktionalitätsanforderungen 

Ein wesentliches funktionales Qualitätskriterium ist der Komfort bei der Navigation innerhalb eines aufgefundenen Dokuments.
Die folgenden Navigationsmöglichkeiten gelten als Basisanforderungen: 

* Ansteuern eines beliebigen Images 
* Anfang: Springen an den Anfang eines Dokuments 
* Ende: Springen an das Ende eines Dokuments 
* Vor: Eine Seite vorgehen 
* Zurück: Eine Seite zurückgehen 
* Volltextrecherche (für Bücher ab 1850 verpflichtend) [56] 
* Metadaten-Info: Hier können Nutzerinnen und Nutzer die Informationen aus den im DMS gespeicherten Beschreibungsfeldern zu „ihrem“ digitalen Dokument einsehen. 
* Hilfe: Über das Hilfemenü sollte eine detaillierte Beschreibung mit Fallbeispielen zur Navigation und für die Suche in der Digital Library zugänglich sein. 

Wenn sachlich möglich und geboten, sind Inhaltsverzeichnisse/Strukturbäume oder funktionale Äquivalente vorzusehen; diese sind grundsätzlich durchsuchbar zu gestalten. 
Wünschenswert sind Navigationshilfen, z.B. grafische Repräsentationen in einer Kopfzeile, die den Nutzerinnen und Nutzern signalisieren, an welcher Stelle des digitalen Dokuments sie sich gerade befinden.
Enthält ein Server Materialien, die konzeptuell in der Benutzung üblicherweise zu übergeordneten Einheiten zusammengefasst werden (mehrbändige Werke), so sollen diese übergeordneten Einheiten als solche sichtbar werden. 


### DFG-Viewer 

Um für die wissenschaftliche Benutzung neben den unterschiedlich gestalteten und dezentral verantworteten Webangeboten der jeweiligen Einrichtungen einen einheitlichen Zugriff auf die Daten (Inhalte) aller DFG-geförderter Digitalisate bieten zu können, werden derzeit zwei sich ergänzende Strategien verfolgt: 

* Festlegung eines einheitlichen Designprofils für die Visualisierung von in DFG-Förderung erstellten Digitalisaten („DFG-Viewer“) 
* Schaffung einer OAI-Schnittstelle mit Unterstützung des METS-Standards: Diese Schnittstelle dient zunächst der einheitlichen Anzeige von Images und ihren Metadaten in DFG-geförderten Projekten und transportiert materialabhängig METS/MODS für Drucke, METS/TEI für Handschriften und METS/EAD für Archivmaterialien. Über diese Schnittstelle werden Funktionen des Weiterblätterns, der Anzeige von Metadaten und andere grundsätzliche Funktionen beschrieben und damit einheitliche Anzeige- und Blätterfunktionen geschaffen, die auch innerhalb von zentralen Nachweisportalen einen homogenen Zugriff auf dezentrale Ressourcen (harvesting) erlauben. 

Zum Zweck der überregionalen Erstpräsentation müssen DFG-geförderte Digitalisierungsvorhaben die genannten Schnittstellen bedienen und/oder den Viewer im DFG-Style an ihrer Einrichtung selbst implementieren.
Die Einrichtung einer OAI-Schnittstelle bleibt davon unberührt.
Anhang A definiert das METS/MODS-Format der Schnittstelle sowie das Viewer-Design. 


[56] Nach dem Stand der gegenwärtigen Technik ist eine OCR-Erkennung bei Drucken der Maschinenpressenzeit ab 1850 verpflichtend. 