## 1. Was macht die Komponente?
* Unterstützt die Benutzer*innen bei der Eingabe mit Vorschlägen.


## 2. Wann soll die Komponente eingesetzt werden?
* Wenn ein Eingabefeld viele vordefinierte Werte aufweisen kann.
* Als Hilfe zur Vorschau bei Suchresultaten/-feldern.


## 3. Regeln
* Die Autocompletion hat immer ein Label.
* Optionale Eingaben werden mit dem Text «(optional)» hinter dem Label versehen. Bei kurzen Feldern kann der Text «(optional)» mit «(opt.)» abgekürzt werden.
* Für detaillierte Erklärungen kann neben dem Label ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein [Tooltip](https://digital.sbb.ch/de/webapps/components/tooltip).
* Während der Eingabe werden direkt Vorschläge eingeblendet (typischerweise nach drei Zeichen, kann aber projektspezifisch angepasst werden).
* Die aufgelisteten Einträge können mittels Pfeiltasten durchlaufen und mit Enter übernommen werden.
* Es werden maximal 10 Vorschläge angezeigt.
* Bei der Auswahl eines Elementes schliesst sich die Autocompletion-Auswahl.


## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Default
* Hover
* Active

### 4.1 Standard
![Darstellung der Komponente Autocomplete in der Standard Ausprägung](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/autocompletion/images/autocompletion_default.png 'class: image')

#### Design Spezifikation
*   [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/8jVp57#Inspector)
*   [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/2q7ekM#Inspector)
*   [Active](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/MVmMnw#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/autocomplete)

### 4.2 Mit Trefferanzeige
Optional zur Standard-Ausprägung kann diese Variante eingesetzt werden, wenn eine Autocompletion-Liste immer mehr als die maximal angezeigten 10 Treffer beinhaltet.
![Darstellung der Komponente Autocomplete mit Trefferanzeige](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/autocompletion/images/Autocompletion_Overflow.png 'class: image')

#### Design Spezifikation
*   [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/5ynoWw#Inspector)
*   [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/bDLaKJ#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/autocomplete)

### 4.3 Mit statischen Einträgen
![Darstellung der Komponente Autocomplete mit statischen Einträgen](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/autocompletion/images/Autocompletion_Static.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/Wjdn3y#Inspector)
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/3LoxEr#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/autocomplete)