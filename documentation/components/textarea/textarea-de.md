## 1. Was macht die Komponente?
* Dient zur Eingabe von grösseren Textmengen in Formularen.


## 2. Wann soll die Komponente eingesetzt werden?
* Wenn von den Benutzer*innen längere Texteingaben verlangt werden.


## 3. Regeln 
* Die Textarea hat immer ein Label.
* Für detaillierte Erklärungen kann neben dem Label ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein [Tooltip](https://digital.sbb.ch/de/webapps/components/tooltip).
* Unten rechts wird die noch verfügbare Anzahl Zeichen angezeigt (ausser die Textarea ist disabled).
* Die Basishöhe kann beim Gestalten des Formulars gesetzt werden.
* Wird der Text länger als die Basishöhe der Textarea, wächst das Element in der Höhe mit dem Inhalt mit.


## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Default
* Focused
* Disabled
* Error
* Mandatory
* Readonly

### 4.1 Standard
![Darstellung der Komponente Textarea](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/textarea/images/Textarea_Default.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/wd5Qaq#Inspector)
* [Focused](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/qLbV42#Inspector)
* [Disabled](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/Lp4nD3#Inspector)
* [Error](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/7P1aJP#Inspector)
* [Mandatory](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/dlwDKn9#Inspector)
* [Readonly](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/agWeyQZ#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/textarea)