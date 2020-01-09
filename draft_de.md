
# Kontext
Wenn wir an einem Projekt teilnehmen, sind wir Teil eines Teams, wir interagieren mit anderen Menschen direkt oder indirekt.
Ob es sich um das Erstellen von Code, die Organisation der Arbeit anderer, die Abstimmung oder Spezifikation handelt,
Dieser Prozess der Interaktion schafft eine Menge von Elementen:
- jedes Mal, wenn eine Kommunikation oder Entscheidung in einem Chat oder einer E-Mail zwischen Menschen stattfindet,
  Inhalte in einer Zeitleiste erstellen,
- jedes Dokument, jede Datei, ob Code, Design oder Dokumentation
- jedes in der Planung definierte Ticket, Epos oder Sprint

All diese Elemente haben unterschiedliche Formen und Eigenschaften:
einen Text, ein Konzept, eine Ticketnummer, eine Datei, eine Funktion in Code,
ein Chat-Kanal, eine Wiki-Seite, ein Link, etc.

alle diese Elemente werden während der Laufzeit des Projekts erstellt, geändert und teilweisse wieder verschwinden.
Die werden miteinander interagieren und Verbindungen zwischeneinandern herstellen

Alle diese Elemente haben in Bezug auf das Projekt gemeinsame Eigenschaften:
- Sichtbarkeit: manchmal sind sie für die Projektmitglieder sichtbar, manchmal bleiben sie unsichtbar.
- Nützlichkeit: sie können für das Projekt nützlich sein, weil sie relevante Informationen für die Durchführung des Projekts enthalten, deshalb wird versucht, sie in Dokumenten, durch Links, Screenshots, Protokolle festzuhalten,
- Ablauf: sie haben eine Lebensdauer und können schnell veralten: ein Link zu einem Dokument mit veralteten Informationen, ein Commit zu einer Datei, die nicht mehr im Repository existiert.

(Kurz gesagt, in einem Projekt gibt es Einheiten, die sich ständig ändern, und zwischen diesen Einheiten gibt es Beziehungen, die sich ständig ändern und durch die Entwicklung des Projekts beeinflusst werden).

Alle am Projekt beteiligten Personen generieren und interagieren ständig mit diesen Elementen, die Informationen enthalten und das Projekt beeinflussen.
Und genau hier liegt das Problem. wissen, welche Elemente/Informationen bereits existieren oder gerade erstellt werden, die für das Projekt relevant sind,
wie diese Informationen verknüpft sind und welche Informationen veraltet sind.

[298]

# Motivation

Wir wissen also, dass es die Notwendigkeit gibt, die Informationen, die in einem Projekt erstellt werden, miteinander zu verbinden, deshalb gibt es nicht nur Hyperlinks zwischen Seiten eines Wikis mit Inhalten,
sondern auch, dass wir über Links auf den Code im Repository zugreifen,
wir uns durch den Code in der IDE bewegen,
wir greifen auf ein Chat-Verlauf,
oder zu eine Beschreibung einer Aufgabe auf einem Ticket, etc. zu.

Diese Verbindungen teilen die gleichen Eigenschaften wie die Elemente selbst: Sichtbarkeit, Nutzen und Ablauf.

In diesem Szenario, von Entitäten und Verbindungen, finden wir daher Probleme, die sich auf die Entwicklung des Projekts beeinflussen:
- Fehlende Kenntnisse der Projektmitglieder über die Existenz von für sie nützlichen Einrichtungen und/oder Beziehungen.
- Kontrolle über die Veralterung von Entitäten und Verbindungen
- Entdeckung relevanter Verbindungen für die Benutzer
- Übersicht und Suche nach Entitäten und Verbindungen, die zu einem bestimmten Zeitpunkt im Projekt vorhanden sind

Die Möglichkeit, den Projektmitgliedern Einblick und Zugang zu relevanten und aktuellen Projektentitäten zu ermöglichen, ist grundlegend
für die korrekte Entwicklung des Projektes

[466]

## Das Semantic Web
Aber..., wir haben bereits Verknüpfungen und Inhalte, reicht das nicht aus?
Natürlich können wir schon jetzt mit mehr oder weniger Aufwand Verknüpfungen herstellen und diese manuell aktualisieren.
Und wenn wir die Verknüpfungen etwas wertvoller machen, indem wir diesen eine Bedeutung geben?
Und wenn wir die feste Struktur der Inhalte, Bereiche und Kanäle verschwinden lassen, so dass der Benutzer die gewünschte Form nach seinen Bedürfnissen geben kann?
Wie im das Semantic Web [1], könnten wir ein System von Dateninteraktion, Vokabularen und Regeln für die Arbeit mit den Daten schaffen.

[563]

# Anwendung
Wir haben bereits alle unsere Inhalte in volatilen Entitäten und Verknüpfungen aufgeteilt,
Wie und wozu kann dies genutzt werden?
Wenn wir über die Nutzung eines Werkzeugs sprechen, müssen wir das Ziel des Benutzers, seine Bedürfnisse und Eigenschaften berücksichtigen.
In einem Projekt haben wir verschiedene Benutzer, mit unterschiedlichen Rollen, Kenntnissen, Berechtigungen, etc.
Für jede von ihnen hat die gleiche Information eine andere Bedeutung und Relevanz.

Nehmen wir an, wir machen eine Website für einen Kunden.
Der Kunde hat eine Reihe von Dokumenten erstellt, eines pro Seite im Web, in jedem dieser Dokumente definiert er: welche Bilder, Texte und andere Elemente wie Formulare, Buttons, etc. verwendet werden müssen.

Als Designer wollen wir wissen, welche Bildformate im gesamten Web verwendet werden. Um das zu machen,
erstellen wir ein eigenes neues Dokument, mit einer Tabelle, die wir mit den Formaten ausfüllen, die vom Kunden in jeder Seite (z.B. 50) definiert wurde.
Wenn wir alle Seiten überprüft haben, haben wir bereits unsere Liste fertig, und wir sind uns 100% sicher, dass der Kunde in dieser Zeit kein Format geändert hat,
dass sich in den nächsten Tagen kein Format ändern wird, oder dass der Kunde uns mitteilen wird, falls sich etwas ändern würde.

.... Wenn wir uns ein Programm im Fernseher ansehen wollen, was uns interessiert, können wir durch die 50 Kanäle zappen und die Zeit verlieren, in der Hoffnung, das zu finden, was wir suchen  
oder wir können direkt zur "Programmliste" gehen und uns einen schnellen Überblick darüber verschaffen was uns interessiert.
Das spart Zeit und führt uns schnell zur Entscheidung.

[828]

Als Programierer ...

# Tool
Metadata|rdf|graph
@todo


[1] https://www.w3.org/standards/semanticweb/
