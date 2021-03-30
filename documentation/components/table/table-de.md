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
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/table)

### 4.2 Sortierbar
Diese Ausprägung hat folgende Zustände:
* Unsorted
* Sorted

![Darstellung der Komponente Tabelle in der Ausprägung Sortierbar](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/table/images/Table_Sortable.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/36ab4f9f-f7f8-436e-9d7e-0f2088e52e04/a/7yV3j3Y#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/table)

### 4.3 Gruppierbar
![Darstellung der Komponente Tabelle in der Ausprägung Gruppierbar](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/table/images/Table_Groupable.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/36ab4f9f-f7f8-436e-9d7e-0f2088e52e04/a/ygLDjDq#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/table)

### 4.4 Selektierbar
Diese Ausprägung hat folgende Zustände:
* Unselected
* EntrySelected
* AllSelected 

![Darstellung der Komponente Tabelle in der Ausprägung Selektierbar](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/table/images/Table_Selectable.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/36ab4f9f-f7f8-436e-9d7e-0f2088e52e04/a/9P53z3p#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/table)

### 4.5 Filterbar
Diese Ausprägung hat folgende Zustände:
* Unfiltered
* Filtered

![Darstellung der Komponente Tabelle in der Ausprägung Filterbar](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/table/images/Table_Filterable.png 'class: image')

* Die einzelnen Spalten können je nach Inhaltstyp (Text, Datum, Wert etc.) mittels den passenden Komponenten ([Textfield](https://digital.sbb.ch/de/webapps/components/textfield), [Datepicker](https://digital.sbb.ch/de/webapps/components/datepicker), [Select](https://digital.sbb.ch/de/webapps/components/select) etc.) gefiltert werden.
* Es kann auch ein übergreifender [Filter](https://digital.sbb.ch/de/webapps/modules/filter) zum Einschränken von grossen Datenmengen eingesetzt werden.

#### Design Spezifikation
* [Default](https://www.sketch.com/s/36ab4f9f-f7f8-436e-9d7e-0f2088e52e04/a/PGRjqjP#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/table)

### 4.6 Inline Aktionen
![Darstellung der Komponente Tabelle in der Ausprägung mit Inline Aktionen](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/table/images/Table_Actions.png 'class: image')

* Beim Hover über Zeilen können Aktionen auf den Elementen angeboten werden.
* Die Aktionen werden mittels [Icon Button](https://digital.sbb.ch/de/webapps/components/button) angeboten. Sie sind ganz rechts in der Tabelle angeordnet und überlagern die letzte Spalte.
* Es sollen maximal 3 Aktionen angeboten werden. Braucht es mehr, sollte ein [Contextmenu](https://digital.sbb.ch/de/webapps/components/contextmenu) verwendet werden.

#### Design Spezifikation
* [Default](https://www.sketch.com/s/36ab4f9f-f7f8-436e-9d7e-0f2088e52e04/a/g07K3Ka#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/table)
