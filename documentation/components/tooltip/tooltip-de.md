## 1. Was macht die Komponente?
* Erlaubt den Benutzer*innen bei Bedarf Erklärungen einzublenden.


## 2. Wann soll die Komponente eingesetzt werden?
* Bei kontextspezifischen Erklärungen zu Interaktionselementen oder Text.


## 3. Regeln
* Der Tooltip besteht aus einem Icon und dem Overlay. Das Info-Icon ist Standard und kann bei Bedarf durch ein anderes Icon ersetzt werden.
* Der Tooltip darf auch auf Texten oder Bildern platziert / zugänglich gemacht werden.
* Das Overlay öffnet sich bei Klick auf das Icon. Alternativ kann der Tooltip auch mittels Hover angezeigt werden.
* Im Overlay dürfen nur Freitext und [Links](https://digital.sbb.ch/de/webapps/components/link) eingesetzt werden. Der Text darf auch als Liste dargestellt werden.
* Der Tooltip-Text darf maximal 300 Zeichen umfassen.
* Das Overlay kann ein 'X'-Icon zum schliessen des Overlays enthalten.
* Das Overlay kann auch wieder ausgeblendet werden, indem irgendwo neben das Overlay geklickt wird.
* Der Spickel des Overlays, der zum Icon zeigt, kann horizontal irgendwo platziert werden (kommt auf die Position des Tooltips auf der Seite an).


## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Hidden
* Hover
* Visible Above
* Visible Underneath
* Visible Left
* Visible Right

### 4.1 Standard
![Darstellung der Komponente Tooltip](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/tooltip/images/Tooltip_Default.png 'class: image')

#### Design Spezifikation
* [Hidden](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/vjRQv1#Inspector)
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/47o5bx#Inspector)
* [Visible Above](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/e0ldqz#Inspector)
* [Visible Underneath](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/GlodpY#Inspector)
* [Visible Left](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/v8JDejb#Inspector)
* [Visible Right](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/4a4dl7Z#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/tooltip)
