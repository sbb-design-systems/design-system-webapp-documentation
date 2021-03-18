## 1. Was macht das Modul?
* Dient zur Nachfrage einer Bestätigung durch den Benutzer.


## 2. Wann soll das Modul eingesetzt werden? 
* Wenn eine Bestätigung einer Aktion durch den Benutzer bestätigt werden muss.


## 3. Regeln
* Die referenzierte Seite wird nicht verlassen.
* Der Dialog hat einen eigenen Header, welcher immer sticky ist.
* Der Dialog hat eine Buttonleiste, welche immer sticky ist. Die primäre Aktion wird links von der sekundären Aktion platziert.
* Im Header dürfen kontextbeschreibende Informationen stehen (beispielsweise die Zug-Nummer).
* Der Inhalt des Dialogs enthält eine detaillierte Beschreibung der Situation und die klare Frage, die der Benutzer beantworten muss.
* Hinter dem Dialog wird ein «Glass» eingeblendet und damit das Editieren ausserhalb des Dialogs blockiert.


## 4. Ausprägungen und Zustände
Das Modul hat folgende Zustände:
* Default

### 4.1 Standard
![Darstellung des Moduls Dialog](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/modules/dialog/images/dialog_default.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/JRAJp5#Inspector)
* Glass: [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/vjRQvb#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/dialog)
