## 1. Was macht das Modul? 
* Bietet den Benutzer*innen jederzeit zugängliche Informationen und Funktionen an.


## 2. Wann soll das Modul eingesetzt werden? 
* Ein Header ist bei jeder Anwendung einzufügen.


## 3. Regeln
* Der Header besteht aus App-Chooser (optional, bei Applikationsgruppen), Umgebungsbanner (ausser Prod), Applikationsname und Version, Hauptnavigation (falls notwendig), Suche (optional), Anzeige für Benachrichtigungen (optional), [Usermenü](https://digital.sbb.ch/de/webapps/components/usermenu) und [Logo](https://digital.sbb.ch/de/webapps/basics/brand).
* Bei Tablet wird die Hauptnavigation in die Burgernavigation verschoben. Bei Mobile zusätzlich noch die Suche, Benachrischtigungen und das Usermenü.
* Der Applikationsname wird bei Mobile mit "..." abgeschnitten, wenn es nicht genügend Platz hat.


## 4. Ausprägungen und Zustände 
### 4.1 Standard
Diese Ausprägung hat folgende Zustände:
* Default

![Darstellung des Moduls Header in der Standard Ausprägung](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/modules/header/images/Header_Default.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/e0ldqj#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/header)

### 4.2 Submenu
Diese Ausprägung hat folgende Zustände:
* Collapsed
* Expanded
* Hover

![Darstellung des Moduls Header in der Ausprägung mit Unternavigation](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/modules/header/images/Header_Submenu.png 'class: image')

#### Design Spezifikation
* [Collapsed](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/AOZRL4#Inspector)
* [Expanded](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/kpKQMP#Inspector)
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/owMDq3#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/header)

### 4.3 Suite
Diese Ausprägung hat folgende Zustände:
* Collapsed
* Expanded

![Darstellung des Moduls Header mit der Navigation einer Suite zum Wechsel zwischen Anwendungen](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/modules/header/images/Header_Suite.png 'class: image')

#### Design Spezifikation
* [Collapsed](https://www.sketch.com/s/271524a1-2f86-4c84-9491-671e5ccd927f/a/gkVMeJ#Inspector)
* [Expanded](https://www.sketch.com/s/271524a1-2f86-4c84-9491-671e5ccd927f/a/8jGL8O#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/header)
