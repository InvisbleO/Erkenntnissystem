**Erstellung**: 2021-02-14  13:32
**Tags**:

# Wörterbuch
= Wörterbuch für komplexere Begriffe ^b64c8b


**dateispezifisch** - bezieht sich nur auf eine Datei und wenn nicht anders gesagt nicht auf einzelne Blöcke, z.B. Themenbereich-Verknüpfung (\#v/sek)  ^ea372c

**Informationseinheiten** - Dateien, Paragraphen mit Überschriften oder Blöcke, also alles was verknüpfbar ist ^92ddaa

## Tags
= einfache Attribute, essenziell ^b984eb

\#v Bestimmung der Art einer Verknüpfung (wird in Klammern hinter einen Link geschrieben)
	-   \#v/log - logische Verknüpfung
	-   \#v/abl - Ableitung (eine grundsätzlich logische Verknüpfung, die Unsicherheiten hat und daher nur prinzipiell/qualitativ zu dem abgeleiteten Ergebnis führen muss, quantitativ kann das Ergebnis abweichen)
	-   \#v/def - Defintion (verlinkt von einem Begriff zu seiner Definition)
		-   wird auch genutzt für alle Stellen, die einfach nur eine andere Stelle verlinken, da das die Defintion ist - Zusätzlich auch genutzt bei [[Wörterbuch#^ea372c|dateispezifischen]]( #v/def) Links, die am Anfang einer Seite stehen, weil da ja gesagt werden muss, dass der Link zur Defintion führt
	-   \#v/zinf - unkategorisierte Zusatzinformation, ungerichtet
	-   \#v/infq - #z/testen ob nötig anstatt /zinf und da es auch embedded gibt, was fast immer Informationsquelle ersetzt 
	-   \#v/spez (ursprünglich Dateiverknüpfung) - dabei wird hinter den Tag die Erklärung zu der Verknüpfung geschrieben
	-   \#v/sek - Für Themenbereiche/Sekundärstruktur einer Datei einzelne verschiedene Tags, z.B. \#v/sek/Gehirn, \#v/sek/Neurologie… 
		-   #z/testen Diese kommen aber nicht hinter eine Verknüpfung, sondern an den Anfang einer Seite (nur Seiten bekommen Themenbereiche, Blöcke wäre zu kompliziert)
-   \#z - Zustand einer Stelle -> bezieht sich also nicht direkt auf den Inhalt, sondern darauf dass an dieser Stelle noch etwas gemacht werden muss
	-   \#z/testen - Aussage muss geprüft werden durch Testen und dann bestätigt oder korrigiert werden - und \#z/todo - Signal, dass eine Stelle nicht als fertig bearbeitet angesehen wird und es wird auf eine Voraussetzung gewartet, damit das gemacht werden kann
		-   z.B. wenn ich mich vorher über ein anderes Thema wie Gefährlichkeit von Coronavirus informieren muss, um eine gute Entscheidung zu treffen, dann tag \#z/todo/CoronavirusGefährlichkeitInformieren - dieser Tag erscheint in der Notiz "Todo" - in dieser wird regelmäßig geprüft, ob für ein todo neue Informationen vorhanden sind, wann es erledigt werden kann - wenn ja, dann dieses Datum planen in Tagesplaner und im Tagesplaner eintragen, worum es sich handelt und wo die Stelle gefunden werden kann
		-   wenn es erledigt ist, dann einfach den tag \#z/todo bzw. testen aus der Stelle, die unvollständig war, entfernen
	-   \#z/irgendwann - Stellen, bei denen ich keinen Zeitpunkt abschätzen kann, weil (1) dieser unabhängig von mir ist, z.B. Entwicklung neuer Obsidian-Features, oder (2) der Zeitpunkt in ferner Zukunft liegt
	- \#z/evtl - für unfertige Ideen, die ich dokumentieren will und auf die ich möglicherweise später zurückkommen will
	- \#z/wirdGelernt - für Systeme, die ich aktuell versuche mir anzugewöhnen, die aber aufgrund dieses Prozesses, mehr Energie und Fokus als gewöhnlich erfordern
	- \#z/nochLernen - für Systeme, die ich schon festgelegt habe, aber die aktuell zu energieraubend zu lernen wären