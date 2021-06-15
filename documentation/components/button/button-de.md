## 1. Was macht die Komponente?
* Löst eine Aktion auf einer Seite aus.


## 2. Wann soll die Komponente eingesetzt werden?
* Beim Starten oder Beenden eines Prozesses.
* Beim Absenden eines Formulars.
* Beim Aufrufen einer Funktion auf einer Seite.


## 3. Regeln
* Darf nicht innerhalb von Fliesstext eingesetzt werden.
* Darf nicht im [Header](https://digital.sbb.ch/de/webapps/modules/header) als Navigation oder Funktion eingesetzt werden.
* Die Mindestbreite beträgt 60px.
* Die Breite wächst mit der Textlänge. Bei mobilen Ansichten ist die Breite 100%.
* Ist der Text beim Erreichen der Maximallänge immer noch zu lang, wird dieser mit «\...» abgekürzt.
* Der Text ist immer einzeilig.
* Buttons werden im Viewport rechtsbündig angeordnet. Der Primary Button wird links vom Secondary Button platziert.


## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Default
* Hover
* On-click
* Disabled

<label class="switch" style="display:none"><input type="checkbox"><span class="slider round"></span></label>

### 4.1 Primary Button
![Darstellung der Komponente Primary Button](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/button/images/button_primary.png 'class: image')
![Darstellung der Komponente Primary Button](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/button/images/button_primary.png 'class: image hide')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/EAeGxd#Inspector)
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/j14rem#Inspector)
* [On-Click](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/dAgjdL#Inspector)
* [Disabled](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/zJyKkM#Inspector)
* [Default](https://www.sketch.com/s/90164eef-96b8-487f-be99-e61e0bf7916d/a/34x0Yw#Inspector 'class: hide')
* [Hover](https://www.sketch.com/s/90164eef-96b8-487f-be99-e61e0bf7916d/a/rvrZPP#Inspector 'class: hide')
* [On-Click](https://www.sketch.com/s/90164eef-96b8-487f-be99-e61e0bf7916d/a/ndDbPk#Inspector 'class: hide')
* [Disabled](https://www.sketch.com/s/90164eef-96b8-487f-be99-e61e0bf7916d/a/QJ1e3Y#Inspector 'class: hide')

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/button)

### 4.2 Alternative Primary Button
![Darstellung der Komponente Alternativer Primary Button](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/button/images/button_primary_alternative.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/ZZVnp3#Inspector)
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/JRAJyk#Inspector)
* [On-Click](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/vjRQr4#Inspector)
* [Disabled](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/47o5kD#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/button)

### 4.3 Secondary Button
![Darstellung der Komponente Secondary Button](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/button/images/Button_Secondary.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/e0ldzP#Inspector)
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/GlodYO#Inspector)
* [On-Click](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/OKeRYm#Inspector)
* [Disabled](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/mYPK0P#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/button)

### 4.4 Ghost Button
![Darstellung der Komponente Ghost Button](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/button/images/button_ghost.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/DaEw94#Inspector)
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/amMazD#Inspector)
* [On-Click](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/AOZR9R#Inspector)
* [Disabled](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/0KA7dG#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/button)

### 4.5 Icon Button
![Darstellung der Komponente Icon Button](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/button/images/Button_Icon.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/DaEw94)
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/amMazD)
* [On-Click](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/AOZR9R)
* [Disabled](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/0KA7dG)

* Beim Hover über einen Icon Button sollte ein [Tooltip](https://digital.sbb.ch/de/webapps/components/tooltip) verwendet werden, um die dahinterliegende Aktion klarer zu machen.

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/button)

### 4.6 Mehrere Aktionen
![Darstellung der Komponente Button bei dem mehrere Aktionen hinterlegt sind](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/button/images/Button_More_Actions.png 'class: image')

* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/aLZ37A#Inspector)
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/OmnVV5v#Inspector)
* [Expanded](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/A57mEx#Inspector)
