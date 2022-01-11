## 1. Was macht die Komponente?
* Strukturierte Darstellung von Daten innerhalb einer Tabelle.


## 2. Wann soll die Komponente eingesetzt werden?
* Einsatz bei der Darstellung von Daten, nicht zur Strukturierung von Content.
* Tabellen sollen so aufgebaut werden, dass diese beim Hinzufügen von Datensätzen in der Vertikalen (Zeilen) wächst.


## 3. Regeln
* Tabellenzellen können entweder nur Information (z.B. Text, Person, Statusanzeige, Icon, ...) oder Interaktionselemente (z.B. Textfeld, Select, Button, ...) enthalten.
* Jede Spalte hat zwingend einen Header (mit Text oder Icon).
* Header können zusätzlich zum Titel noch Untertitel beinhalten.
* Header- und Zeileninhalte können innerhalb der Tabellenzelle links-, rechtsbündig oder zentriert sein: Text linksbündig, Icons zentriert, Zahlen rechtsbündig
* Masseinheiten von Inhalten werden optimalerweise auf der zweiten Zeile des Spaltenheaders eingefügt. Alternativ können sie direkt neben der Spaltenheader-Bezeichnung in runden Klammern angezeigt.
* Horizontales Scrolling sollte wo möglich vermieden werden.
* Spalten können zu logischen Gruppen zusammengefasst werden. Zwischen gruppierten Spalten gibt es keine Trennlinie.
* Mittels [Pagination](https://digital.sbb.ch/de/webapps/components/pagination) können grosse Datenmengen aufgeteilt werden. Alternativ kann je nach Bedarf auch ein Infinite Scrolling verwendet werden.
* Tastaturbedienung: Zwischen den Zeilen kann mittels Pfeiltasten (hoch, runter) navigiert werden.

## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Default
* Hover
* Active

### 4.1 Standard
![Darstellung der Komponente Tabelle in der Standard Ausprägung](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/table/images/Table_Default.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/36ab4f9f-f7f8-436e-9d7e-0f2088e52e04/a/L0b3V3y#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/table?variant=lean)

### 4.2 Sortierbar
Diese Ausprägung hat folgende Zustände:
* Unsorted
* Sorted

![Darstellung der Komponente Tabelle in der Ausprägung Sortierbar](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/table/images/Table_Sortable.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/36ab4f9f-f7f8-436e-9d7e-0f2088e52e04/a/7yV3j3Y#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/table?variant=lean)

### 4.3 Gruppierbar
![Darstellung der Komponente Tabelle in der Ausprägung Gruppierbar](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/table/images/Table_Groupable.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/36ab4f9f-f7f8-436e-9d7e-0f2088e52e04/a/ygLDjDq#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/table?variant=lean)

### 4.4 Selektierbar
Diese Ausprägung hat folgende Zustände:
* Unselected
* EntrySelected
* AllSelected 

![Darstellung der Komponente Tabelle in der Ausprägung Selektierbar](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/table/images/Table_Selectable.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/36ab4f9f-f7f8-436e-9d7e-0f2088e52e04/a/9P53z3p#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/table?variant=lean)

### 4.5 Filtrierbar
Diese Ausprägung hat folgende Zustände:
* Unfiltered
* Filtered

![Darstellung der Komponente Tabelle in der Ausprägung Filterbar](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/table/images/Table_Filterable.png 'class: image')

* Die einzelnen Spalten können je nach Inhaltstyp (Text, Datum, Wert etc.) mittels den passenden Komponenten ([Textfield](https://digital.sbb.ch/de/webapps/components/textfield), [Datepicker](https://digital.sbb.ch/de/webapps/components/datepicker), [Select](https://digital.sbb.ch/de/webapps/components/select) etc.) gefiltert werden.
* Es kann auch ein übergreifender [Filter](https://digital.sbb.ch/de/webapps/modules/filter) zum Einschränken von grossen Datenmengen eingesetzt werden.
* Es empfiehlt sich, die Anzahl der gefilterten Elemente den Benutzer*innen anzuzeigen, z.B. "34 von 3890"

#### Design Spezifikation
* [Default](https://www.sketch.com/s/36ab4f9f-f7f8-436e-9d7e-0f2088e52e04/a/PGRjqjP#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/table?variant=lean)

### 4.6 Inline Aktionen
![Darstellung der Komponente Tabelle in der Ausprägung mit Inline Aktionen](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/table/images/Table_Inline_Actions.png 'class: image')

* Beim Hover über Zeilen bzw. Fokussierung mittels Tab-Navigation über die Tastatur können Aktionen auf den Elementen angeboten werden.
* Die Aktionen werden mittels [Icon Button](https://digital.sbb.ch/de/webapps/components/button) angeboten. Je nach Anwendungsfall wird entschieden, in welcher Spalte (erste oder letzte Spalte) sie platziert werden. Dort überlagern sie jeweils den bestehenden Content.
* Es sollen maximal 3 Aktionen angeboten werden. Braucht es mehr, sollte ein [Contextmenu](https://digital.sbb.ch/de/webapps/components/contextmenu) verwendet werden.
* Tastaturbedienung: Bei Fokus auf einer Zeile der Tabelle kann mittels 'Tab' auf die Aktionen gesprungen werden.

#### Design Spezifikation
* [Default](https://www.sketch.com/s/36ab4f9f-f7f8-436e-9d7e-0f2088e52e04/a/g07K3Ka#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/table?variant=lean)

### 4.7 Übergreifende Aktionen
![Darstellung der Komponente Tabelle in der Ausprägung mit übergreifenden Aktionen](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/table/images/Table_Batch_Actions.png 'class: image')

* Bei (Mehrfach-)Selektion von Elementen können übergreifende Aktionen angeboten werden.
* Für die Aktionen können alle Ausprägungen von [Buttons](https://digital.sbb.ch/de/webapps/components/button) verwendet werden.
* Die primäre Aktion ist links, die sekundären Aktionen stehen rechts davon.
* Es sollen maximal 3 Aktionen angeboten werden. Braucht es mehr, sollte ein [Contextmenu](https://digital.sbb.ch/de/webapps/components/contextmenu) verwendet werden.
* Die übergreifenden Aktionen werden rechts oberhalb der Tabelle angeordnet.

#### Design Spezifikation
* [Default](https://www.sketch.com/s/36ab4f9f-f7f8-436e-9d7e-0f2088e52e04/a/zxl7l35#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/table?variant=lean)


## 5. Beispielanwendung
![Darstellung eines Beispiels einer Tabelle mit Sortierung, Selektierung, Filterung, Paging und übergeordneten Aktionen](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/table/images/Table_Showcase.png 'class: image')