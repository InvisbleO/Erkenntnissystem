**Erstellung**: 2021-02-12  15:31
**Tags**:
**Links**:

---

# Aufbau + Workflow Logik-&Wissenssystem

= grobes Verzeichnis des Logik&Wissenssystems + Definition von Struktur und Arbeitsregeln

Aktueller Zweck des Logik&-&Erkenntnissystems ist alle meine Gedanken und Erkenntnisse zu speichern, sodass ich sie barrierelos verstehen kann, sowie ein Werkzeug für neue Ideen zu sein. ^1dbf82

## Aufbau des Systems + Grundprinzipien
### Kategorisierung und Einordnung von Daten
#### Ordner
-   wird angesehen als eine zusätzliche Möglichkeit Daten zu sortieren einfach grundsätzlich verwenden für Einordnung von Dateien, falls ich eine bestimmte Art von Datei suche kann es behilflich sein, ansonsten aber unwichtig
	-   Nachteil dass Rüberspringen zu Nachbardateien in Primärstruktur nicht so einfach ist, falls dass ein großes Hindernis ist, dann Eltern- und Kinderdateien in einer Datei verlinken, aber vorerst nicht erwartet dass es nötig sein wird
	-   Alternative wäre hierarchische tagstruktur (z.B. \#root/subfolder/subsubfolder) - hat aber eher Nachteile, dass  außerhalb von Obsidian keine Struktur vorhanden ist und die Navigation schwieriger ist und keine klaren Vorteile
-   wichtige Ordner erklärt:
##### 1 Gedanken
![[Ordnung von Gedanken (Ordner)#^01f23c]]
##### 2 Hintergrunddaten
alle Daten, die nicht systemrelevant sind oder mit Erkenntnissen und alltäglichen Handlungen zu tun haben, z.B. Fotos von Personalausweis etc.
##### 3 Systemrelevante Daten (Obsidian + Erkenntnissystem)
Dateien, die innerhalb von Obsidian eine Rolle spielen, z.B. Datenbank für Mediendateien

##### 4-x Einzelne Dateien mit spezifischer Bedeutung, Erklärung weiter unten
**[[Todo]]**:
Seite, die alle Aufgaben enthält, denen noch kein Zeitpunkt zugeordnet werden kann (nachdem diese aus der Tagesnotiz in Todo übertragen wurden)

**[[Aufbau + Workflow Logik-&Wissenssystem]]**: "README", enthält alle Informationen für Zurechtfindung im System ^7dcbbe

**[[Testen und Updaten!]]**: 
enthält alle aktuellen Tests (sowohl mit Datum als auch ohne) und auf welche Stellen sie sich auswirken

**[[Wörterbuch]]**:
für komplexere Begriffe, diese Begriffe dann mit dem Eintrag im Wörterbuch verbinden ^00f7b0

#### Links
-   normale Links bedeuten, dass ein Konzept oder ein Begriff vorausgesetzt wird in der aktuellen Datei und dass diese in dem Link nachgelesen werden können
	-   Wenn der gleiche Begriff genutzt wird, dann ist das der Link, wenn ein anderer Begriff genutzt wird, dann ist dieser entweder ein alias oder wird verlinkt)
	-   Links befinden sind immer bei dem Ziel einer Verknüpfung, bei der Voraussetzung können sie unter Backlinks nachgeschaut werden
	-   Hinter jedem normalen Link steht ein Tag, der die Art der Verknüpfung beschreibt z.B. \[\[Albert Einstein\]\](\#v/def) bis auf Links, die zu einer Informationseinheit führen, die genau das beinhaltet, was der Linkname bedeutet - wenn sie zusätzlich eine Defintion oder andere bestimmte Daten beinhaltet, dann entsprechenden # hinter die Verknüpfung schreiben
-   Embedded Link bedeutet, dass der Inhalt einer anderen Datei in der aktuellen Datei inhaltlich genutzt wird, z.B. bei Schlussfolgerungen - es ist egal wo der Ursprung der Datei/des Blocks ist (also wo das Original gespeichert ist)
	-   erfordern keinen Tag, da man ja weiß, was der Inhalt ist in dem Moment in dem ihn sich ansieht
-   Unmentioned Links sind irrelevant für Verständnis

#### [[Wörterbuch#Tags|Tags]]
![[Wörterbuch#^b984eb]] ( #v/def)
#### Codezeichen
-    im Titel (zur Kategorisierung der Datei, theoretisch auch in Überschriften von Blöcken möglich)
-   Vorerst nicht, nur bei Bedarf

### Verlinkung von Daten
Grundprinzip: **Bottom->Up**
Die konkretesten Dateien sind nach Möglichkeit immer die Quelle von Informationen (d.h. sie enthalten die originalen [[Wörterbuch#^92ddaa|Informationseinheiten]] ( #v/def)). Andere Informationseinheiten, die weniger konkrete oder weniger zu dem Thema zutreffende Informationen enthalten, können die Informationseinheit mit den konkretesten Daten referenzieren
- Bsp.: in dieser Datei stehen Erklärungen zu den wichtigsten Ordnern des Systems, aber in den Ordnern gibt es Dateien, die die Ordnung noch konkreter erklären, daher muss auf diese referenziert/verknüpft werden
- wäre zu chaotisch, Informationen zu einem Thema über viele nicht aufeinanderfolgende Informationseinheiten zu verteilen, hat keine Übersicht und schwieriger zu suchen, wenn man eine Information verlinken will

## Dateiformatierung
- Dateiname: eindeutig und möglichst kurz, Schlüsselwörter in Klammern dahinter möglich, falls sie Suchalgorithmus helfen #z/testen
- Struktur: #z/testen
	- dateispezifische Tags, Attribute und Links stehen für jede Datei identisch nach dem festen Muster einer [[Allgemeine Dateivorlage]] an einer Stelle der Datei
	- wenn möglich überschriften für Primärstruktur nutzen, da sie Verlinkung von Blöcken ermöglichen
	- Listen mit Anstrichen oder Nummerierung für alles, was keine weitere Unterteilung in Blöcke erfordert 
	-  Wenn keine Hierarchie möglich ist, sondern es eine kausale Kette ist, dann diese als Folge von Blöcken, die voneinander getrennt sind, von denen jeder vermutlich nicht mehr aufgeteilt wird
		-  Vorteil davon ist auch, dass im Gegenzug zu einer Kausalkette als Liste andere Blöcke relativ nahtlos zitiert werden können
- Regeln:
	- entsprechend des [[#^1dbf82|Zweck des Systems]] ( #v/def) keine spezifischen Regeln für Sprache, außer dass alle Stellen so formuliert sein müssen, dass ich sie jederzeit verstehen kann
		- Beispiele sind hilfreich um sich in den Gedanken hineinzuversetzen, ausreichend erklären
	- [[#^00f7b0|Wörterbuch]] zur Erklärung von Begriffen
		- diese Begriffe müssen, wenn sie verwendet werden nicht mit dem Eintrag im Wörterbuch verbunden werden, Hauptsache der Eintrag kann im Wörterbuch gefunden werden
	- Sprache (Wortwahl, etc.) #z/todo

## Workflow
### Allgemeingültig
- Wenn ein Block bearbeitet wird, der verlinkt ist, und der Block mit einem unteren Block verbunden wird, dann muss die Block-ID manuell an das Ende des neu entstandenen Blocks kopiert werden, damit die Verlinkung noch funktioniert

### Ideaspace
- ![[Ordnung von Gedanken (Ordner)#Workflow]]

### Shortcuts
-   Notizen immer wenn möglich in Bearbeitungsmodus ansehen
-   CMD-O Quick Switcher
-   CMD-Shift-F: Suche
-   CMD-> /<-: vorherige Seite
-   Suche: (https://publish.obsidian.md/help/Plugins/Search)
	-   "" - Wörter müssen aneinanderhängend gefunden werden
	-   \ um Zeichen nur als Zeichen zu nutzen und nicht mit der mit ihnen verknüpften Funktion
	-   logische Operatoren: "OR", "-" und " "
	-   "()" für mehrere queries
	-   "file:" für Dateiname, "path:" für alle Dateien in einem Ordner, 
-   Wenn ich eine Datei löschen muss, dann idealerweise vorher alle Links dazu aufheben, indem ich an den entsprechenden Stellen die Klammern entferne
	-   ansonsten können Links auch nachträglich aufgehoben werden
-   Bald gibt es ein Update: Wenn ein Dateiname geändert wird, dann ändert sich auch der Name im Link - gilt es dann für alle Links? #z/irgendwann

### Mobile Workflow
- #z/testen wird Tagesnotiz automatisch morgens erstellt? Mache ich vllt automatisch, da Traumjournal immer am Computer
- manuelle Suche

## Weiteres
- Versionierung und Autobackup geschieht über GitHub (alle 5 min)
	- Setup: https://medium.com/analytics-vidhya/how-i-put-my-mind-under-version-control-24caea37b8a5 + external Obsidian plugin für Git

