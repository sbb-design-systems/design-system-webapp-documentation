## 1. Was macht die Komponente?
Kategorisiert eine grosse Anzahl an Informationen.


## 2. Wann soll die Komponente eingesetzt werden? 
* Beim Filtern von Ergebnissen mit vielen Kategorien.


## 3. Regeln
* Ein Tag hat immer einen Indikator, welcher angibt wie viele Ergebnisse dahinterstecken.
* Der Begriff im Tag ist immer einzeilig (keine Zeilenumbrüche) und das Tag selber wächst in der Breite mit dem Text mit.
* Wird ein Tag aufgrund des Textes zu lang für den Viewport, wird der Text mit «...» gekürzt.


## 4. Ausprägungen und Zustände 
Die Komponente hat folgende Zustände:
* Active
* Inactive

### 4.1 Filtertag
![Darstellung der Komponente Tag zur Verwendung als Filter](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/tag/images/Tag_Filter.png 'class: image')

* Im Filter sind die Tags im aktiven und inaktiven Zustand vorhanden.
* Mit Klick auf ein Tag toggelt der jeweilige Zustand in den anderen und beeinflusst so das Filterergebnis.
* Innerhalb des Filter wird immer zusätzlich ein Tag «Alle» eingefügt. Wird dieses Filtertag angeklickt, wechselt es in den Zustand aktiv und alle anderen Tags im Filter werden in den Zustand inaktiv gesetzt.

#### Design Spezifikation
* [Active](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/YzZ5Lm#Inspector)
* [Inactive](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/K10Rmg#Inspector)
