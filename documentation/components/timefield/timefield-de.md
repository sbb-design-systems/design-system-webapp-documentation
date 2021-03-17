## 1. Was macht die Komponente?
* Dient zur Eingabe einer Uhrzeit.


## 2. Wann soll die Komponente eingesetzt werden?
* Immer wenn vom Benutzer eine Uhrzeit verlangt wird.


## 3. Regeln 
* Standardmässig ist die aktuelle Uhrzeit vorausgefüllt, ausser es macht im Kontext des Einsatzes keinen Sinn.
* Die Zeiteingabe kann ohne Eingabe des Doppelpunktes geschehen. Eingaben wie 130, 1.30 oder 1,30 werden nach verlassen des Feldes korrekt in 01:30 umformatiert.


## 4. Ausprägungen und Zustände 
Die Komponente hat folgende Zustände:
* Default
* Hinted
* Focused
* Disabled
* Mandatory

### 4.1 Standard
![Darstellung der Komponente Zeiteingabe](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/timefield/images/timefield_default.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/nKQDql#Inspector)
* [Hinted](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/QqD1pb#Inspector)
* [Focused](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/xz0Qe0#Inspector)
* [Disabled](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/EAeGYq#Inspector)
* [Mandatory](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/eKKqqKP#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/time-input)
