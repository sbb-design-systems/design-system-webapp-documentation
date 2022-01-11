## 1. Was macht das Modul?
* Erwirkt für spezifische Entscheidungen eine Handlung der Benutzer*innen.


## 2. Wann soll das Modul eingesetzt werden? 
* Zur Anzeige von kritischen Informationen, welche die Benutzer*innen bestätigen müssen.
* Zur Nachfrage von Aktionen, welche die Benutzer*innen bestätigen müssen.
* Zur Auswahl von Entscheidoptionen durch die Benutzer*innen.


## 3. Regeln
### 3.1 Verhalten
* Dialoge werden als Modal-Fenster vor die Anwendung angezeigt.
* Dialoge deaktivieren alle Anwendungsfunktionen und bleiben solange eingeblendet bis sie bestätigt wurden, abgebrochen wird oder eine notwendige Handlung ausgeführt wurde.
* Dialoge sind absichtlich unterbrechend, daher sollten sie sparsam eingesetzt werden.
* Der Dialog kann über verschiedene Wege geschlossen und damit die Aktion abgebrochen werden:
    * über das 'X' rechts im Header des Dialogs
    * über einen Klick auf das «Glass» im Hintergrund
    * über einen "Abbrechen"-Button (falls vorhanden)
    * 'ESC'-Taste der Tastatur

### 3.2 Layout
* Der Dialog hat einen eigenen Header, einen Inhaltsbereich und eine Buttonleiste.
* Es sollte verhindert werden, dass gescrollt werden muss. Lässt es sich nicht verhindern, so sind Header und Buttonleiste sticky.
* Die primäre Aktion wird links von der sekundären Aktion platziert.
* Hinter dem Dialog wird ein «Glass» eingeblendet und damit das Editieren ausserhalb des Dialogs blockiert.

### 3.3 Inhalt
* Im Header dürfen kontextbeschreibende Informationen stehen (beispielsweise die Zugnummer).
* Der Inhalt des Dialogs ist komplett flexibel nutzbar, z.B.
    * eine detaillierte Beschreibung der Situation und die klare Frage, welche die Benutzer*innen beantworten müssen.
    * ein Formular, um ein komplexes Datenobjekt zu erstellen oder zu bearbeiten.

### 3.4 Aktionen
* Bestätigungsaktionen sind so lange disabled bis eine Auswahl getroffen wurde, oder das Formular valid ist (alle Pflichtfelder ausgefüllt und keine falschen Eingaben).
* Abbruch-Aktionen werden nie disabled.


## 4. Ausprägungen und Zustände
### 4.1 Simple (Warnungen / Bestätigungen)
Diese Ausprägung hat folgende Zustände:
* Default

![Darstellung des Moduls Dialog in der Ausprägung Simple](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/modules/dialog/images/Dialog_Simple.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/36ab4f9f-f7f8-436e-9d7e-0f2088e52e04/a/gkVMoM#Inspector)
* Glass: [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/vjRQvb#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/dialog?variant=lean)

### 4.2 Complex (Formulare)
Diese Ausprägung hat folgende Zustände:
* Valid
* Not Valid

![Darstellung des Moduls Dialog in der Ausprägung Complex](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/modules/dialog/images/Dialog_Complex.png 'class: image')

* Diese Ausprägung dient zur Erstellung oder Bearbeitung von komplexen Datenobjekten, wenn diese nicht direkt im Content der Applikation bearbeitet werden können.
* Wenn die Benutzer*innen den Dialog verwerfen möchten und ...
    * keine Änderungen vorgenommen wurden, wird das Dialogfeld geschlossen und es ist keine Bestätigung erforderlich.
    * die Benutzer*innen Änderungen vorgenommen haben, werden die Benutzer*innen aufgefordert, die Verwerfungsaktion zu bestätigen.

#### Design Spezifikation
* [Valid / Not Valid](https://www.sketch.com/s/36ab4f9f-f7f8-436e-9d7e-0f2088e52e04/a/ZOW5MWJ#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/dialog?variant=lean)