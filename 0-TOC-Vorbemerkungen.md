# DFG-Praxisregeln �Digitalisierung�

DFG-Vordruck 12.151 � 12/16 � Praxisregeln �Digitalisierung�

## Inhaltsverzeichnis 

Vorbemerkung zu den Praxisregeln �Digitalisierung� 4 

1. Pr�fliste f�r Antragstellende und f�r die Begutachtung 4 
  1.1 Allgemeine technische Abl�ufe/Voraussetzungen 5 
  1.2 Technische Parameter der digitalen Reproduktion 6 
  1.3 Metadaten 6 
  1.4 Volltextgenerierung 8 
  1.5 Langzeitverf�gbarkeit 8 
  1.6 Organisatorische Fragen 9 
  1.7 Zitieren, persistente Adressierung 9 
  1.8 Bereitstellung der Metadaten und Digitalisate f�r die �ffentlichkeit 9 
2. Ziele und Auswahl 11 
  2.1 Ziele 11 
  2.2 Auswahl 12 
  2.3 Dublettenpr�fung und Datenabgleich bei der Retrodigitalisierung publizierter Texte 13 
3. Digitalisierung 13 
  3.1 Bereitstellung der Materialien, konservatorische Pr�fung 14 
  3.2 Technische Parameter der digitalen Reproduktion 14 
    3.2.1 Allgemeine Erl�uterungen und Parameter 14 
      3.2.1.1 Aufl�sung 15 
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
    3.3.1 Erschlie�ung, deskriptive Metadaten 31 
    3.3.2 Strukturelle Metadaten f�r digitale Faksimiles 32 
    3.3.3 Sammlungs- und Bestandsbeschreibung 33 
    3.3.4 Austausch und Weitergabe der Metadaten 33 
  3.4 Volltextgenerierung 34 
    3.4.1 Texterfassung 34 
    3.4.2 Zeichenkodierung 37 
    3.4.3 Markup von Volltexten 38 
    3.4.4 Layout 38 
  3.5 Langzeitverf�gbarkeit 39 
4. Organisatorische Fragen � Eigendigitalisierung versus Digitalisierung in Dienstleistung 40 
5. Zitieren digitaler Ressourcen, persistente Adressierung 41 
6. Bereitstellung der Projektergebnisse f�r die �ffentlichkeit 42 
  6.1 Rechte, Lizenzierung und Open Access 42 
  6.2 Mindestanforderungen f�r die Bereitstellungssysteme von Digitalisaten 44 
    6.2.1 Funktionalit�tsanforderungen 44 
    6.2.2 Technische Mindestanforderungen 45 
7. Pr�sentationsstandards f�r Textwerke, DFG-Viewer 45 
  7.1 Basisanforderungen und Architektur 46 
  7.2 Funktionalit�tsanforderungen 46 
  7.3 DFG-Viewer 47 
* Anhang A: METS/MODS-Profil f�r die Darstellung im DFG-Viewer und �bermittlung per OAI 
* Anhang B: METS/TEI-Spezifikation f�r die Darstellung von digitalisierten Handschriften 
* Anhang C: LIDO-Kernelemente f�r die Publikation 
* Anhang D: Sammlungs- und Bestandsbeschreibung 
 


# Vorbemerkung zu den Praxisregeln �Digitalisierung� 

Die Deutsche Forschungsgemeinschaft (DFG) [1] f�rdert im Bereich der Wissenschaftlichen Literaturversorgungs- und Informationssysteme (LIS) Projekte an wissenschaftlichen Einrichtungen, insbesondere Service- und Informationseinrichtungen in Deutschland.
F�rderziel ist der Aufbau leistungsf�higer Informationssysteme und -infrastrukturen f�r die Forschung unter �berregionalen Gesichtspunkten.
Die Ergebnisse der Projekte sollen f�r die Wissenschaft frei und dauerhaft zug�nglich sein. 
 
Ziel der Praxisregeln �Digitalisierung� im F�rderbereich LIS ist es, Antragstellenden die Planung von Digitalisierungsprojekten zu erleichtern und die Begutachtung von Antr�gen vergleichbar zu gestalten.
Die Praxisregeln wollen keine H�rden aufbauen, sondern durch die Formulierung von Standards einen Beitrag zur Nachhaltigkeit und Zukunftsf�higkeit der unterst�tzen Projekte leisten. 

Die Standards erg�nzend finden sich in den Praxisregeln auch weiterf�hrende Ausf�hrungen, beispielsweise zur konservatorischen Pr�fung der zur Digitalisierung vorgesehenen Materialien, zum Erheben von Metadaten, zur Herstellung der Digitalisate, zur Indexierung von Bildinhalten, zur Herstellung von Volltexten oder auch zur Perspektive der Langzeitsicherung digitaler Inhalte. 

Im Folgenden werden in Kapitel 1 knapp die wichtigsten Anforderungen zusammengefasst.
Abweichungen von den dort beschriebenen Regeln sind zwar m�glich, m�ssen aber im Einzelfall begr�ndet werden.
In den Kapiteln 2 bis 6 findet sich eine grunds�tzliche und weiter ausholende Einf�hrung in die Probleme und Vorgehensweisen, die sich f�r Projekte stellen, die Objekte aus Bibliotheken, Archiven oder musealen Sammlungen in digitale Form �berf�hren wollen.
Diese Kapitel wenden sich bewusst auch an Personen, die derartige Projekte neu planen, also unter Umst�nden �ber keine detaillierten Vorkenntnisse verf�gen.
Kapitel 7 verweist auf f�r textuelle Objekte erforderliche DFG-Pr�sentationsstandards und Formate. 


[1] Die Deutsche Forschungsgemeinschaft (DFG) ist die zentrale Selbstverwaltungseinrichtung der Wissenschaft zur F�rderung der Forschung an Hochschulen und �ffentlich finanzierten Forschungsinstitutionen in Deutschland.
Die DFG dient der Wissenschaft in allen ihren Zweigen durch die finanzielle Unterst�tzung von Forschungsvorhaben und durch die F�rderung der Zusammenarbeit unter den Forschern (http://www.dfg.de).
Die DFG unterst�tzt auch Vorhaben zur Verbesserung der wissenschaftlichen Informations-Infrastrukturen in Deutschland.
Die Ergebnisse der gef�rderten Projekte sollen f�r die Wissenschaft frei und dauerhaft zug�nglich sein (http://www.dfg.de/lis).
Zu beachten ist, dass die definierten Tr�geraufgaben und -finanzierungen der antragstellenden Einrichtungen durch die F�rderung nicht substituiert werden d�rfen.
Projekte m�ssen daher in ihrer Profilierung �ber die regul�ren Grundaufgaben einer Einrichtung hinausgehen, zeitlich und inhaltlich begrenzt sein sowie herausragende und �berregional bedeutende Materialien zum Gegenstand haben.
Nicht f�rderf�hig sind damit Vorhaben, die vorrangig der Kulturf�rderung, Kulturgutvermittlung oder vergleichbaren Zielsetzungen dienen, sowie kommerziell orientierte Projekte. 