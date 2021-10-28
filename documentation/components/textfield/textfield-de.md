## 1. Was macht die Komponente?
* Dient zur Eingabe von Texten und Zahlen.


## 2. Wann soll die Komponente eingesetzt werden?
* Wenn von den Benutzer*innen eine Eingabe benötigt wird.


## 3. Regeln 
* Ein Eingabefeld hat immer ein Label.
* Für detaillierte Erklärungen kann neben dem Label ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein [Tooltip](https://digital.sbb.ch/de/webapps/components/tooltip).
* Der Eingabetext ist immer einzeilig.
* Wird der Text während der Eingabe länger als die Breite des Eingabefeldes wird der geschriebene Text nach links verdrängt, damit das aktuell Geschriebene immer gesehen wird.
* Nach dem Verlassen des Eingabefeldes mit einem langen Text wird dieser am Ende abgeschnitten und mit «...» gekennzeichnet.
* Ein Eingabefeld kann einen Hinweistext (Placeholder) enthalten, welcher direkt im Eingabefeld angezeigt wird, solange von den Benutzer*innen kein Wert eingetragen wurde.
* Können die Benutzer*innen ein Formularfeld nie bearbeiten, so darf kein Eingabefeld verwendet werden (Darstellung als Text).


## 4. Ausprägungen und Zustände 
Das Element hat folgende Zustände:
* Default
* Placeholder
* Focused
* Disabled
* Error
* Mandatory
* Readonly

### 4.1 Standard
![Darstellung der Komponente Textfeld in der Standard Ausprägung](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/textfield/images/Textfield_Default.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/Pw1oL8#Inspector)
* [Placeholder](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/gk1ZRj#Inspector)
* [Focused](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/8jVpv8#Inspector)
* [Disabled](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/2q7erA#Inspector)
* [Error](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/MVmMa7#Inspector)
* [Mandatory](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/5ynozd#Inspector)
* [Readonly](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/AxL1rj4#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/field)

### 4.2 Passworteingabe
![Darstellung der Komponente Textfeld zur Passworteingabe](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/textfield/images/textfield_password.png 'class: image')
* Das Eingabefeld in der Ausprägung «Passwort» stellt keinen Zustand «Placeholder» zur Verfügung.

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/bDLaWj#Inspector)
* [Focused](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/WjdnLk#Inspector)
* [Disabled](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/3Loxjm#Inspector)
* [Error](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/r79reA#Inspector)

### 4.3 Löschbar
![Darstellung der Komponente Textfeld mit der Möglichkeit zu direktem Löschen des Werts](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/textfield/images/Textfield_Clearable.png 'class: image')

#### Design Spezifikation
* [Empty](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/zxWKVEo#Inspector)
* [Value](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/ZOlnaWx#Inspector)
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/JnoJxzG#Inspector)
