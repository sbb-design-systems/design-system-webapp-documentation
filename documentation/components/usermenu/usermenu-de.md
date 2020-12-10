## 1. Was macht die Komponente?
* Dient zum An-/Abmelden, zur Rolleauswahl und bietet dem angemeldeten Benutzer ein Menü mit übergreifenden Funktionalitäten an.


## 2. Wann soll die Komponente eingesetzt werden?
* Immer wenn sich der Benutzer bei einer Anwendung anmelden können soll.


## 3. Regeln
* Das Benutzermenü ist immer im Header platziert und darf nur dort eingesetzt werden.
* Das aufgeklappte Benutzermenü kann durch Klick ausserhalb des Dropdowns geschlossen werden.
* Der letzte Menüpunkt in der Liste ist immer «Abmelden».


## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* LoggedOut
* Collapsed
* Expanded
* Hover

### 4.1 Standard
![Darstellung der Komponente Benutzermenü in der Standard Ausprägung](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/usermenu/images/Usermenu_Default.png 'class: image')

#### Design Spezifikation
* [LoggedOut](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/OKeRP8#Inspector)
* [Collapsed](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/mYPKqz#Inspector)
* [Expanded](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/DaEwqq#Inspector)
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/j14rq0#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/usermenu)

### 4.2 Rollenauswahl
![Darstellung der Komponente Benutzermenü mit Rollenauswahl](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/usermenu/images/Usermenu_Rollenauswahl.png 'class: image')

#### Design Spezifikation
* [LoggedOut](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/dAgjqZ#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/usermenu)
