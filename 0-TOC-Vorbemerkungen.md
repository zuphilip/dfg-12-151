# DFG-Praxisregeln „Digitalisierung“

DFG-Vordruck 12.151 – 02/13 - Praxisregeln „Digitalisierung“

## Inhaltsverzeichnis 

Vorbemerkung zu den Praxisregeln „Digitalisierung“ 4 

* 1. Ziele und Auswahl 5 
  * 1.1 Ziele 5 
  * 1.2 Auswahl 5 
  * 1.3 Dublettenprüfung und Datenabgleich bei der Retrodigitalisierung publizierter Texte 6 
* 2. Digitalisierung 7 
  * 2.1 Bereitstellung der Materialien, konservatorische Prüfung 7 
  * 2.2 Technische Parameter der digitalen Reproduktion 8 
    * 2.2.1 Allgemeine Erläuterungen und Parameter 8 
      * 2.2.1.1 Auflösung 8 
      * 2.2.1.2 Farbtiefe 10 
      * 2.2.1.3 Digitaler Aufnahmeablauf 11 
      * 2.2.1.4 Dateiformate 15 
    * 2.2.2 Materialspezifische Parameter 17 
      * 2.2.2.1 Textwerke 17 
      * 2.2.2.2 Grafische Darstellungen 17 
      * 2.2.2.3 Fotografien 18 
      * 2.2.2.4 Mikroformen 21 
      * 2.2.2.5 Dreidimensionale Objekte 21 
  * 2.3 Metadaten 25 
    * 2.3.1 Erschließung, deskriptive Metadaten 27 
    * 2.3.2 Strukturelle Metadaten für digitale Faksimiles 27 
    * 2.3.3 Sammlungs- und Bestandsbeschreibung 28 
    * 2.3.4 Austausch und Weitergabe der Metadaten 29 
  * 2.4 Volltextgenerierung 30 
    * 2.4.1 Texterfassung 30 
    * 2.4.2 Zeichenkodierung 34 
    * 2.4.3 Markup von Volltexten 34 
    * 2.4.4 Layout 35 
  * 2.5 Langzeitverfügbarkeit 35 
* 3. Organisatorische Fragen 37 
* 4. Zitieren digitaler Ressourcen, persistente Adressierung 39 
* 5. Bereitstellung der Digitalisate für die Öffentlichkeit 40 
  * 5.1 Rechteklärung und Open Access 40 
  * 5.2 Mindestanforderungen für die Bereitstellungssysteme von Digitalisaten 41 
    * 5.2.1 Funktionalitätsanforderungen 41 
    * 5.2.2 Technische Mindestanforderungen 42 
* 6. Präsentationsstandards für Textwerke, DFG-Viewer 43 
  * 6.1 Basisanforderungen und Architektur 43 
  * 6.2 Funktionalitätsanforderungen 44 
  * 6.3 DFG-Viewer 44 
* 7. Prüfliste für Antragsteller und Gutachter 45 
  * 7.1 Allgemeine technische Abläufe/Voraussetzungen 46 
  * 7.2 Technische Parameter der digitalen Reproduktion 46 
  * 7.3 Metadaten 47 
  * 7.4 Volltextgenerierung 48 
  * 7.5 Langzeitverfügbarkeit 49 
  * 7.6 Organisatorische Fragen 49 
  * 7.7 Zitieren, persistente Adressierung 50 
  * 7.8 Bereitstellung der Digitalisate für die Öffentlichkeit 50 
* 8. Regeln für die Durchführung von Digitalisierungsprojekten 51 
* Anhang A: METS/MODS-Profil für die Darstellung im DFG-Viewer und Übermittlung per OAI 
* Anhang B: METS/TEI-Spezifikation für die Darstellung von digitalisierten Handschriften 
* Anhang C: LIDO-Kernelemente für die Publikation 
* Anhang D: Sammlungs- und Bestandsbeschreibung 


## Vorbemerkung zu den Praxisregeln „Digitalisierung“ 

Die Deutsche Forschungsgemeinschaft (DFG) [1] fördert im Bereich der Wissenschaftlichen Literaturversorgungs- und Informationssysteme (LIS) Projekte an wissenschaftlichen Einrichtungen, insbesondere Service- und Informationseinrichtungen in Deutschland.
Förderziel ist der Aufbau leistungsfähiger Informationssysteme für die Forschung unter überregionalen Gesichtspunkten.
Die Ergebnisse der Projekte sollen für die Wissenschaft frei und dauerhaft zugänglich sein. 

Ziel der Praxisregeln „Digitalisierung“ im Förderbereich LIS ist es, Antragstellern die Planung von Digitalisierungsprojekten zu erleichtern und die Begutachtung von Anträgen vergleichbar zu gestalten.
Die Praxisregeln wollen keine Hürden aufbauen, sondern durch die Formulierung von Standards einen Beitrag zur Nachhaltigkeit und Zukunftsfähigkeit der unterstützen Projekte leisten. 
 
Die Standards ergänzend finden sich in den Praxisregeln auch weiterführende Ausführungen, beispielsweise zur konservatorischen Prüfung der zur Digitalisierung vorgesehenen Materialien, zum Erheben von Metadaten, zur Herstellung der Digitalisate, zur Indexierung von Bildinhalten, zur Herstellung von Volltexten oder auch zur Perspektive der Langzeitsicherung digitaler Inhalte. 

Im Folgenden wird in den Kapiteln 1 bis 5 eine grundsätzliche und weiter ausholende Einführung in die Probleme und Vorgehensweisen gegeben, die sich für Projekte stellen, die Materialien aus Bibliotheken, Archiven oder musealen Sammlungen in digitale Form überführen wollen.
Diese Kapitel wenden sich bewusst auch an Personen, die derartige Projekte neu planen, also unter Umständen über keine detaillierten Vorkenntnisse verfügen.
Kapitel 6 verweist auf für textuelle Materialien erforderliche DFG-Präsentationsstandards und Formate.
In Kapitel 7 sind knapp noch einmal die wichtigsten Anforderungen zusammengefasst.
Abweichungen von den dort beschriebenen Regeln sind zwar möglich, müssen aber im Einzelfall begründet werden.
In Kapitel 8 werden abschließend wichtige Verfahrens-Regeln für die Durchführung eines DFG-Vorhabens benannt. 

Auch wenn dies im Folgenden öfter wiederholt werden wird, ist ein Prinzip so wichtig, dass es explizit vorangestellt werden soll: Die wissenschaftlich motivierte Digitalisierung wird nicht als neue Technik, sondern als Normalfall verstanden.
In der Praxis bedeutet dies für die Konzeption von Projekten, dass es zwar weiterhin wichtig ist, Digitalisate zu erzeugen, deren Qualität den Anforderungen der die Digitalisate nutzenden Forschung genügt, dass aber gleichzeitig auch darauf zu achten ist, dass die gewählten Vorgehensweisen effektiv und kostenbewusst genug sind, um systematisch auf große Mengengerüste angewendet werden zu können. 


[1] Die Deutsche Forschungsgemeinschaft (DFG) ist die zentrale Selbstverwaltungseinrichtung der Wissenschaft zur Förderung der Forschung an Hochschulen und öffentlich finanzierten Forschungsinstitutionen in Deutschland.
Die DFG dient der Wissenschaft in allen ihren Zweigen durch die finanzielle Unterstützung von Forschungsvorhaben und durch die Förderung der Zusammenarbeit unter den Forschern (http://www.dfg.de).
Die DFG unterstützt auch Vorhaben zur Verbesserung der wissenschaftlichen Informations-Infrastrukturen in Deutschland.
Die Ergebnisse der geförderten Projekte sollen für die Wissenschaft frei und dauerhaft zugänglich sein (http://www.dfg.de/lis).
Zu beachten ist, dass die definierten Trägeraufgaben und -finanzierungen der antragstellenden Einrichtungen durch die Förderung nicht substituiert werden dürfen.
Projekte müssen daher in ihrer Profilierung über die regulären Grundaufgaben einer Einrichtung hinausgehen, zeitlich und inhaltlich begrenzt sein sowie herausragende und überregional bedeutende Materialien zum Gegenstand haben.
Nicht förderfähig sind damit Vorhaben, die vorrangig der Kulturförderung, Kulturgutvermittlung oder vergleichbaren Zielsetzungen dienen, sowie kommerziell orientierte Projekte. 
