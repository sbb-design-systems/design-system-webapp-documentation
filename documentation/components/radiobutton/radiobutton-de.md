## 1. Was macht die Komponente?
* Dient zur Auswahl genau einer Option aus mehreren.


## 2. Wann soll die Komponente eingesetzt werden?
* Bei zwei und mehr Auswahlmöglichkeiten, bei der sich die Optionen gegenseitig ausschliessen.


## 3. Regeln
* Ein Radiobutton ist nur innerhalb eines Formulars erlaubt.
* Es müssen mindestens zwei Optionen zur Auswahl stehen.
* Eine Vorauswahl ist Pflicht.
* Radiobuttons können vertikal oder horizontal angeordnet werden. Die vertikale Anordnung wird bevorzugt, dadurch können die Benutzer*innen die Auswahlmöglichkeiten schneller erfassen.
* Der Text kann mehrzeilig sein.
* Nebst dem eigentlichen Radiobutton dient auch der gesamte Text als Click-Target.
* Oberhalb einer Radiobutton-Gruppe kann ein Titel eingesetzt werden.
* Für detaillierte Erklärungen zu einer Radiobutton-Gruppe kann neben dem Titel ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein [Tooltip](https://digital.sbb.ch/de/webapps/components/tooltip).


## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Checked
* Unchecked
* Focused Checked
* Focused Unchecked
* Disabled Checked
* Disabled Unchecked

### 4.1 Standard
![Darstellung der Komponente Radiobutton](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/radiobutton/images/radiobutton_default.png 'class: image')

#### Design Spezifikation
* [Checked](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/9dlW0z#Inspector)
* [Unchecked](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/Pw1oM8#Inspector)
* [Focused checked](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/gk1Z5j#Inspector)
* [Focused unchecked](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/8jVp08)
* [Disabled checked](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/2q7elA#Inspector)
* [Disabled unchecked](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/MVmM87#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/radio-button)
