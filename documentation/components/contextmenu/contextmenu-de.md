## 1. Was macht die Komponente?
* Bietet kontextspezifische Aktionen an, entweder dynamisch per Maus-Rechtsklick auf ein Element oder statisch über ein Icon.


## 2. Wann soll die Komponente eingesetzt werden?
* Wenn auf einem Objekt je nach Zustand oder Rolle des Benutzers Aktionen zur effizienten Ausführung angeboten werden sollen.


## 3. Regeln
* Ein Contextmenu kann über die rechte Maustaste oder ein Icon angeboten werden.
* Das Contextmenu kann Icons enthalten, muss aber nicht.
* Auf einer Ebene des Contextmenu gibt es entweder bei allen Menuitems ein Icon oder bei keinem. 
* Menuitems können gruppiert werden. Gruppen werden durch einen Strich getrennt.
* Ein Contextmenu kann zur Sortierung von Elementen genutzt werden. In diesem Fall wird mittels Pfeil gezeigt, nach welchem Attribut in welche Richtung sortiert ist.
* Es ist erlaubt, auch tiefere Ebenenstrukturen anzubieten. Es sollte aber darauf geachtet werden, dass je mehr Verschachtelung, desto ineffizienter die Bedienung.


## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Default
* Hover

### 4.1 Standard
Diese Ausprägung hat zusätzlich folgende Zustände:
* Expanded (optional)

![Darstellung der Komponente Kontextmenü zum Öffnen mittels rechter Maustaste](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/contextmenu/images/contextmenu_default.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/8jVpO7#Inspector)
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/2q7eZM#Inspector)
* [Expanded](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/MVmMKw#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/contextmenu)

### 4.2 Icon
Diese Ausprägung hat zusätzlich folgende Zustände:
* Expanded Hover Underneath
* Expanded Hover Above

![Darstellung der Komponente Kontextmenü zum Öffnen mittels Icon](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/contextmenu/images/contextmenu_icon.png 'class: image')

* Als Icon werden standardmässig die drei Punkte verwendet. 

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/5yno4w#Inspector)
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/bDLaZJ#Inspector)
* [Expanded Hover Underneath](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/Wjdnly#Inspector)
* [Expanded Hover Above](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/3LoxJr#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/contextmenu)

### 4.3 Sorting
Diese Ausprägung hat zusätzlich folgende Zustände:
* Expanded Hover
* Expanded Active

![Darstellung der Komponente Kontextmenü zur Sortierung von Inhalten](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/contextmenu/images/Contextmenu_Sorting.png 'class: image')
* Zur Anzeige der Sortierung wird das Pfeil-Icon verwendet.
* Per Default wird absteigend (ascending) sortiert.
* Beim Hover auf aktiv sortiertes Attribut wird das Pfeil-Icon gedreht.
* Der ganze Menueintrag (Name und Icon) ist klickbar.

#### Design Spezifikation
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/r79r07#Inspector)
* [Active](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/nKQDWd#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/contextmenu)
