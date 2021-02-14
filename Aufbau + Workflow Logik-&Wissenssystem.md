
# Aufbau + Workflow Logik-&Wissenssystem

## Aufbau des Systems + Grundprinzipien

### Kategorisierung und Einordnung von Daten
#### Ordner
-   wird angesehen als eine zusätzliche Möglichkeit Daten zu sortieren einfach grundsätzlich verwenden für Einordnung von Dateien, falls ich eine bestimmte Art von Datei suche kann es behilflich sein, ansonsten aber unwichtig
	-   Nachteil dass Rüberspringen zu Nachbardateien in Primärstruktur nicht so einfach ist, falls dass ein großes Hindernis ist, dann Eltern- und Kinderdateien in einer Datei verlinken, aber vorerst nicht erwartet dass es nötig sein wird
	-   Alternative wäre hierarchische tagstruktur (z.B. \#root/subfolder/subsubfolder) - hat aber eher Nachteile, dass  außerhalb von Obsidian keine Struktur vorhanden ist und die Navigation schwieriger ist und keine klaren Vorteile
-   Ordnerstruktur erklärt:
	-   **Gedanken**: Hauptordner, enthält alle für Erkenntnisse oder alltägliche Handlungen sowie für Arbeitsprozess relevanten Daten
		-   **Ideaspace**: Ort für Informationen, an denen ich arbeite (die ich miteinandner und mit bereits eingeordneten Informationen verknüpfe, die ich selber noch nicht fertig eingeordnet habe)(Workfow: [[#Ideaspace]]( #v/def)
		-   **Prinzipien & Systeme**
		-   **Tagesnotizen**:
			-   sind Quick Capture System sowie Ort für täglich wiederholende Ereignisse, die keine genaue Unterteilung in einzelne Blöcke erfordern
				- Traumjournal, andere Journale
				- Erinnerungen
			- Gedanken aus Quick capture werden regelmäßig analysiert und in passende Notizen eingeordnet, aber sie bleiben auch unverändert in der Tagesnotiz stehen, damit ich später sehen kann, wie sich mein Denkensprozess verändert hat etc.
			- Sollen als Dokumentation meines Lebens dienen
			- Vorlage: [[Vorlage Tagesnotizen]]
		- **Weltbild**: alle Erkenntnisse von Grund auf, Logiksystem
	-   **Hintergrunddaten**: alle Daten, die nicht systemrelevant sind oder mit Erkenntnissen und alltäglichen Handlungen zu tun haben, z.B. Fotos von Personalausweis etc.
	-   **System**: Dateien, die innerhalb von Obsidian eine Rolle spielen, z.B. Datenbank für Mediendateien
	-   Einzelne Dateien mit spezifischer Bedeutung, Erklärung weiter unten

#### Links
-   normale Links bedeuten, dass ein Konzept oder ein Begriff vorausgesetzt wird in der aktuellen Datei und dass diese in dem Link nachgelesen werden können
	-   Wenn der gleiche Begriff genutzt wird, dann ist das der Link, wenn ein anderer Begriff genutzt wird, dann ist dieser entweder ein alias oder wird verlinkt)
	-   Links befinden sind immer bei dem Ziel einer Verknüpfung, bei der Voraussetzung können sie unter Backlinks nachgeschaut werden
	-   Hinter jedem normalen Link steht ein Tag der die Art der Verknüpfung beschreibt z.B. \[\[Albert Einstein\]\](\#Informationsquelle)
-   Embedded Link bedeutet, dass der Inhalt einer anderen Datei in der aktuellen Datei inhaltlich genutzt wird, z.B. bei Schlussfolgerungen - es ist egal wo der Ursprung der Datei/des Blocks ist (also wo das Original gespeichert ist)
-   Unmentioned Links sind irrelevant für Verständnis

#### Tags
-   \#v Bestimmung der Art einer Verknüpfung
	-   \#v/log - logische Verknüpfung
	-   \#v/abl - Ableitung (eine grundsätzlich logische Verknüpfung, die Unsicherheiten hat und daher nicht sicher zu dem abgeleiteten Ergebnis führen muss)
	-   \#v/def - Defintion
	-   \#v/infq
	-   \#v/spez (ursprünglich Dateiverknüpfung) - dabei wird hinter den Tag die Erklärung zu der Verknüpfung geschrieben
	-   \#v/sek Für Themenbereiche/Sekundärstruktur einzelne verschiedene Tags, z.B. \#v/sek, \#v/sek/Neurologie… - Diese kommen aber nicht hinter eine Verknüpfung, sondern an den Anfang einer Seite (nur Seiten bekommen Themenbereiche, Blöcke wäre zu kompliziert)
-   \#z Zustand einer Notiz/eines Blocks - einfache Attribute
	-   \#z/testen - Aussage muss geprüft werden durch Testen und dann bestätigt oder korrigiert werden
	-   \#z/todo - Signal, dass eine Stelle nicht als fertig bearbeitet angesehen wird und es wird auf eine Voraussetzung gewartet, damit das gemacht werden kann
		-   z.B. wenn ich mich vorher über ein anderes Thema wie Gefährlichkeit von Coronavirus informieren muss, um eine gute Entscheidung zu treffen, dann tag \#z/todo/CoronavirusGefährlichkeitInformieren - dieser Tag erscheint in der Notiz "Todo" - in dieser wird regelmäßig geprüft, ob für ein todo neue Informationen vorhanden sind, wann es erledigt werden kann - wenn ja, dann dieses Datum planen und wenn es erledigt ist, dann einfach den tag \#z/todo aus der Stelle, die unvollständig war, entfernen

#### Codezeichen
-    im Titel (zur Kategorisierung der Datei, theoretisch auch in Überschriften von Blöcken möglich)
-   Vorerst nicht, nur bei Bedarf

## Dateiformatierung
- Dateiname: #z/testen
- Struktur: #z/testen
	- wenn möglich überschriften für Primärstruktur nutzen, da sie Verlinkung von Blöcken ermöglichen
		- unter Überschrift eine Zeile Platz lassen, damit darunter ein eigenständiger Block ist
	-	Listen mit Anstrichen oder Nummerierung für alles, was keine weitere Unterteilung in Blöcke erfordert 
	-  Wenn keine Hierarchie möglich ist, sondern es eine kausale Kette ist, dann diese als Folge von Blöcken, die voneinander getrennt sind, von denen jeder vermutlich nicht mehr aufgeteilt wird
		-  Vorteil davon ist auch, dass im Gegenzug zu einer Kausalkette als Liste andere Blöcke relativ nahtlos zitiert werden können
- Regeln: #z/todo
	- z.B. rechtschreibung, Sprache

## Workflow
### Ideaspace
- #z/testen
- fertige Dateien oder Blöcke werden in einen der anderen Ordner eingeordnet


Wenn ein Block bearbeitet wird, der verlinkt ist, und der Block mit einem unteren Block verbunden wird, dann muss die Block-ID manuell an das Ende des neu entstandenen Blocks kopiert werden, damit die Verlinkung noch funktioniert

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
-   Bald gibt es ein Update: Wenn ein Dateiname geändert wird, dann ändert sich auch der Name im Link - gilt es dann für alle Links?

### Mobile Workflow
- wird Tagesnotiz automatisch morgens erstellt? Mache ich vllt automatisch, da Traumjournal immer am Computer
- manuelle Suche

## Weiteres
- Versionierung und Autobackup geschieht über GitHub (alle 5 min)
	- Setup: https://medium.com/analytics-vidhya/how-i-put-my-mind-under-version-control-24caea37b8a5 + external Obsidian plugin für Git

