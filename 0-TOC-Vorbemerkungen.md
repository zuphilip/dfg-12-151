# DFG-Praxisregeln „Digitalisierung“

DFG-Vordruck 12.151 – 12/16 – Praxisregeln „Digitalisierung“

## Inhaltsverzeichnis 

Vorbemerkung zu den Praxisregeln „Digitalisierung“ 4 

1. Prüfliste für Antragstellende und für die Begutachtung 4 
  1.1 Allgemeine technische Abläufe/Voraussetzungen 5 
  1.2 Technische Parameter der digitalen Reproduktion 6 
  1.3 Metadaten 6 
  1.4 Volltextgenerierung 8 
  1.5 Langzeitverfügbarkeit 8 
  1.6 Organisatorische Fragen 9 
  1.7 Zitieren, persistente Adressierung 9 
  1.8 Bereitstellung der Metadaten und Digitalisate für die Öffentlichkeit 9 
2. Ziele und Auswahl 11 
  2.1 Ziele 11 
  2.2 Auswahl 12 
  2.3 Dublettenprüfung und Datenabgleich bei der Retrodigitalisierung publizierter Texte 13 
3. Digitalisierung 13 
  3.1 Bereitstellung der Materialien, konservatorische Prüfung 14 
  3.2 Technische Parameter der digitalen Reproduktion 14 
    3.2.1 Allgemeine Erläuterungen und Parameter 14 
      3.2.1.1 Auflösung 15 
      3.2.1.2 Farbtiefe 16 
      3.2.1.3 Digitaler Aufnahmeablauf 17 
      3.2.1.4 Dateiformate 20 
    3.2.2 Materialspezifische Parameter 22 
      3.2.2.1 Textwerke 22 
      3.2.2.2 Grafische Darstellungen 23 
      3.2.2.3 Fotografien 23 
      3.2.2.4 Mikroformen 26 
      3.2.2.5 Dreidimensionale Objekte 26 
  3.3 Metadaten 30 
    3.3.1 Erschließung, deskriptive Metadaten 31 
    3.3.2 Strukturelle Metadaten für digitale Faksimiles 32 
    3.3.3 Sammlungs- und Bestandsbeschreibung 33 
    3.3.4 Austausch und Weitergabe der Metadaten 33 
  3.4 Volltextgenerierung 34 
    3.4.1 Texterfassung 34 
    3.4.2 Zeichenkodierung 37 
    3.4.3 Markup von Volltexten 38 
    3.4.4 Layout 38 
  3.5 Langzeitverfügbarkeit 39 
4. Organisatorische Fragen – Eigendigitalisierung versus Digitalisierung in Dienstleistung 40 
5. Zitieren digitaler Ressourcen, persistente Adressierung 41 
6. Bereitstellung der Projektergebnisse für die Öffentlichkeit 42 
  6.1 Rechte, Lizenzierung und Open Access 42 
  6.2 Mindestanforderungen für die Bereitstellungssysteme von Digitalisaten 44 
    6.2.1 Funktionalitätsanforderungen 44 
    6.2.2 Technische Mindestanforderungen 45 
7. Präsentationsstandards für Textwerke, DFG-Viewer 45 
  7.1 Basisanforderungen und Architektur 46 
  7.2 Funktionalitätsanforderungen 46 
  7.3 DFG-Viewer 47 
* Anhang A: METS/MODS-Profil für die Darstellung im DFG-Viewer und Übermittlung per OAI 
* Anhang B: METS/TEI-Spezifikation für die Darstellung von digitalisierten Handschriften 
* Anhang C: LIDO-Kernelemente für die Publikation 
* Anhang D: Sammlungs- und Bestandsbeschreibung 
 


# Vorbemerkung zu den Praxisregeln „Digitalisierung“ 

Die Deutsche Forschungsgemeinschaft (DFG) [1] fördert im Bereich der Wissenschaftlichen Literaturversorgungs- und Informationssysteme (LIS) Projekte an wissenschaftlichen Einrichtungen, insbesondere Service- und Informationseinrichtungen in Deutschland.
Förderziel ist der Aufbau leistungsfähiger Informationssysteme und -infrastrukturen für die Forschung unter überregionalen Gesichtspunkten.
Die Ergebnisse der Projekte sollen für die Wissenschaft frei und dauerhaft zugänglich sein. 
 
Ziel der Praxisregeln „Digitalisierung“ im Förderbereich LIS ist es, Antragstellenden die Planung von Digitalisierungsprojekten zu erleichtern und die Begutachtung von Anträgen vergleichbar zu gestalten.
Die Praxisregeln wollen keine Hürden aufbauen, sondern durch die Formulierung von Standards einen Beitrag zur Nachhaltigkeit und Zukunftsfähigkeit der unterstützen Projekte leisten. 

Die Standards ergänzend finden sich in den Praxisregeln auch weiterführende Ausführungen, beispielsweise zur konservatorischen Prüfung der zur Digitalisierung vorgesehenen Materialien, zum Erheben von Metadaten, zur Herstellung der Digitalisate, zur Indexierung von Bildinhalten, zur Herstellung von Volltexten oder auch zur Perspektive der Langzeitsicherung digitaler Inhalte. 

Im Folgenden werden in Kapitel 1 knapp die wichtigsten Anforderungen zusammengefasst.
Abweichungen von den dort beschriebenen Regeln sind zwar möglich, müssen aber im Einzelfall begründet werden.
In den Kapiteln 2 bis 6 findet sich eine grundsätzliche und weiter ausholende Einführung in die Probleme und Vorgehensweisen, die sich für Projekte stellen, die Objekte aus Bibliotheken, Archiven oder musealen Sammlungen in digitale Form überführen wollen.
Diese Kapitel wenden sich bewusst auch an Personen, die derartige Projekte neu planen, also unter Umständen über keine detaillierten Vorkenntnisse verfügen.
Kapitel 7 verweist auf für textuelle Objekte erforderliche DFG-Präsentationsstandards und Formate. 


[1] Die Deutsche Forschungsgemeinschaft (DFG) ist die zentrale Selbstverwaltungseinrichtung der Wissenschaft zur Förderung der Forschung an Hochschulen und öffentlich finanzierten Forschungsinstitutionen in Deutschland.
Die DFG dient der Wissenschaft in allen ihren Zweigen durch die finanzielle Unterstützung von Forschungsvorhaben und durch die Förderung der Zusammenarbeit unter den Forschern (http://www.dfg.de).
Die DFG unterstützt auch Vorhaben zur Verbesserung der wissenschaftlichen Informations-Infrastrukturen in Deutschland.
Die Ergebnisse der geförderten Projekte sollen für die Wissenschaft frei und dauerhaft zugänglich sein (http://www.dfg.de/lis).
Zu beachten ist, dass die definierten Trägeraufgaben und -finanzierungen der antragstellenden Einrichtungen durch die Förderung nicht substituiert werden dürfen.
Projekte müssen daher in ihrer Profilierung über die regulären Grundaufgaben einer Einrichtung hinausgehen, zeitlich und inhaltlich begrenzt sein sowie herausragende und überregional bedeutende Materialien zum Gegenstand haben.
Nicht förderfähig sind damit Vorhaben, die vorrangig der Kulturförderung, Kulturgutvermittlung oder vergleichbaren Zielsetzungen dienen, sowie kommerziell orientierte Projekte. 