# Java Data Structures – ArrayList & LinkedList

## Projektbeschreibung

Dieses Java-Lernprojekt beschäftigt sich mit der eigenen Implementierung grundlegender Datenstrukturen.

Ziel ist es, die interne Funktionsweise dynamischer Arrays und verketteter Listen besser zu verstehen, anstatt ausschließlich die fertigen Collections der Java-Standardbibliothek zu verwenden.

## Implementierte Datenstrukturen

### 1. MyArrayList

Eine eigene Implementierung eines dynamischen Arrays für Ganzzahlen.

Funktionen:
- Hinzufügen von Elementen mit `add()`
- Automatische Vergrößerung des internen Arrays
- Suche nach Elementen mit `contains()`
- Ausgabe des Array-Inhalts mit `toString()`

### 2. MyArrayListHomeWork

Eine erweiterte Übungsimplementierung auf Basis eines `Object[]`-Arrays.

Funktionen:
- Einfügen von Elementen an einer bestimmten Position
- Entfernen von Elementen anhand ihres Index
- Verschieben von Elementen innerhalb des Arrays
- Automatische Kapazitätserweiterung
- Indexprüfung mit `IndexOutOfBoundsException`

### 3. MyLinkedList

Eine grundlegende Implementierung einer verketteten Liste.

Funktionen:
- Erstellen von Listenknoten mit der Klasse `Node`
- Hinzufügen von Elementen am Listenende
- Verknüpfung der Knoten über `next` und `last`
- Zugriff auf den ersten Knoten über `getHead()`

## Verwendete Technologien

- Java
- Objektorientierte Programmierung (OOP)
- Arrays
- Referenzen und verkettete Datenstrukturen
- Exception Handling

## Projektstruktur

- `src/MyArrayList.java` – Dynamisches Array
- `src/MyArrayListHomeWork.java` – Erweiterte ArrayList-Übungen
- `src/LinkedList/MyLinkedList.java` – Verkettete Liste
- `src/LinkedList/Node.java` – Listenknoten
- `src/Main.java` – Beispiele zur Verwendung von Java-Collections

## Lernziele

- Unterschiede zwischen Arrays und verketteten Listen verstehen
- Dynamische Speicherverwaltung auf Array-Basis nachvollziehen
- Referenzen zwischen Objekten verwenden
- Elemente einfügen, suchen und entfernen
- Datenstrukturen selbst implementieren

## Projektstatus

Das Projekt wurde im Rahmen praktischer Java-Übungen erstellt.

Die Implementierungen dienen Lernzwecken und bilden noch nicht den vollständigen Funktionsumfang der Java-Standardbibliothek ab.

### Geplante Verbesserungen

- Weitere Methoden wie `get()`, `set()` und `remove()` ergänzen
- Generics (`<T>`) verwenden
- Automatisierte Tests mit JUnit hinzufügen
- Fehlerbehandlung und Randfälle überprüfen
- Beispiele zur Zeitkomplexität der Operationen dokumentieren
