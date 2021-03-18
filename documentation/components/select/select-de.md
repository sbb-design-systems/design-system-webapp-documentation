## 1. Was macht die Komponente?
* Dient zur Auswahl einer oder mehrerer Optionen aus einer vorgegebenen Liste.


## 2. Wann soll die Komponente eingesetzt werden?
* Bei einer Auswahl aus mehreren Optionen (Einfach- oder Mehrfachauswahl) einer Liste.
* Wenn eine Auswahl getroffen werden muss, bei der sich die Einträge gegenseitig ausschliessen und kein Defaultwert gesetzt werden soll (anders als beim Element [Radiobutton](https://digital.sbb.ch/de/webapps/components/radiobutton).
* Wenn Auswahloptionen gruppiert werden sollen.


## 3. Regeln
* Es müssen mindestens zwei Optionen zur Auswahl stehen.
* Das Element hat immer ein Label.
* Für detaillierte Erklärungen kann neben dem Label ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein [Tooltip](https://digital.sbb.ch/de/webapps/components/tooltip).
* Der Text im Select-Element ist immer einzeilig.
* Ist ein Eintrag länger als die verfügbare Breite des Elements, wird der Text des Eintrages mit «...» abgekürzt.
* Bei einem Pflichtfeld ist eine Vorauswahl nicht erlaubt.
* Wenn noch keine Auswahl getroffen wurde, lautet der Element-Text «Bitte wählen...».


## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Default
* Hinted
* Focused
* Disabled
* Error
* Mandatory
* Expanded

### 4.1 Standard
![Darstellung der Komponente Select in der Standard Ausprägung](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/select/images/Select_Default.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/5ynoRd#Inspector)
* [Hinted](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/v88vv84#Inspector)
* [Focused](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/bDLaGj#Inspector)
* [Disabled](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/Wjdn2k#Inspector)
* [Error](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/3LoxWm#Inspector)
* [Mandatory](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/4aabbaD#Inspector)
* [Expanded](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/r79r5A#Inspector)
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/nKQDZl#Inspector)
* [Active](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/QqD1Mb#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/select)

### 4.2 Mehrfachauswahl 
![Darstellung de rKomponente Select mit Mehrfachauswahl](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/select/images/select_multi.png 'class: image')

#### Design Spezifikation
* [Collapsed](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/xz0QA0#Inspector)
* [Expanded](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/EAeGJq#Inspector)
* [Expanded Autocomplete](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/j14rpb#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/select)

### 4.3 Gruppierte Einfachauswahl
![Darstellung der Komponente Select mit gruppierten Einträgen](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/select/images/Select_Grouped_Single.png 'class: image')

#### Design Spezifikation
* [Expanded](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/dAgjMj#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/select)

### 4.4 Gruppierte Mehrfachauswahl
![Darstellung der Komponente Select mit gruppierten Einträgen und Mehrfachauswahl](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/select/images/Select_Grouped_Multi.png 'class: image')

#### Design Spezifikation
* [Expanded](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/zJyK5l#Inspector)
* [Expanded Tree Checkbox](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/ZZVnLv#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/select)
