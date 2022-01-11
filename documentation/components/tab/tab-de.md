## 1. Was macht die Komponente?
* Dient zur Strukturierung der Anzeige von Daten und Formularen.


## 2. Wann soll die Komponente eingesetzt werden?
* Wenn innerhalb des gleichen Kontexts zwischen verschiedenen Aspekten gewechselt werden soll.
* Wenn die Inhalte der verschiedenen Aspekte nicht gleichzeitig von den Benutzer*innen angesehen werden müssen.


## 3. Regeln
* Per Default ist immer das erste Register ausgewählt.
* Die Registerbezeichungen sind immer einzeilig.
* Die Registerbezeichung sollte möglichst kurz und prägnant sein, damit die Themen schnell erfasst werden können.
* Falls die Register für den Viewport zu lang sind, wird die Breite verkürzt und die Bezeichungen werden mit «...» abgeschnitten. Ein Hover über den Tab blendet den kompletten Namen in einem [Tooltip](https://digital.sbb.ch/de/webapps/components/tooltip) ein.
* Ein weiteres Tab-Modul innerhalb eines Registers (Tab-in-Tab) ist nicht erlaubt.


## 4. Ausprägungen und Zustände 
Die Komponente hat folgende Zustände:
* Active
* Inactive
* Hover
* Disabled

### 4.1 Standard
![Darstellung der Komponente Tab](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/tab/images/tab_default.png 'class: image')

#### Design Spezifikation
* [Active](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/47o5dx#Inspector)
* [Inactive](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/e0ldMz#Inspector)
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/Glod4Y#Inspector)
* [Disabled](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/OKeRL8#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/tabs?variant=lean)