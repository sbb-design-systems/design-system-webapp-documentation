## 1. Was macht die Komponente?
* Stellt Werte und Kategorien als kompakte Elemente dar.


## 2. Wann soll die Komponente eingesetzt werden?
* Wenn es in einem Formular möglich sein soll, zu einem Attribut mehrere Werte zu setzen.
* Wenn nach Kategorien gefiltert werden soll.


## 3. Regeln
* Der Begriff im Chip ist immer einzeilig (keine Zeilenumbrüche) und der Chip selber wächst in der Breite mit dem Text mit.
* Wird ein Chip aufgrund des Textes zu lang für den Viewport, wird der Text mit «...» gekürzt.
* Die Chips werden in einem [Textfield](https://digital.sbb.ch/de/webapps/components/textfield) dargestellt. Dieses kann je nach Anzahl Chips und vorhandenem Platz auch mehrzeilig werden.
* Mittels Backspace können Chips im Textfield gelöscht werden.
* Je nach Anwendungsfall können die Chips über "autocomplete"-Auswahlen oder mit Freitext generiert werden.

## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Active
* Disabled
* Hover
* Focused

### 4.1 Input
![Darstellung der Komponente Chip als Eingabewert](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/chip/images/chip_input.png 'class: image')

#### Design Spezifikation
* [Active](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/yZ9QzA#Inspector)
* [Disabled](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/9dlWmn#Inspector)
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/Pw1onQ#Inspector)
* [Focused](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/gk1ZGz#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/chips?variant=lean)