## 1. Was macht die Komponente?
* Dient zur Anzeige von Meldungen, welche eine ganze Seite oder ein Modul einer Anwendung betreffen.


## 2. Wann soll die Komponente eingesetzt werden?
* Wenn Benutzer*innen auf einer Seite eine Aktion ausgelöst haben und vom System ein Feedback erhalten soll.
* Oder wenn ein technisches Problem besteht, das die Benutzer*innen am Arbeiten hindert.


## 3. Regeln
* Notifications erscheinen immer erst nach dem Auslösen einer Aktion durch die Benutzer*innen.
* Die Breite kann sich nach der Breite eines Formulars, dem ganzen Content-Bereich oder einer Standardbreite beim Ensatz als Toast richten.
* Die Höhe richtet sich nach der Textlänge der Meldung.
* Werden die Benutzer*innen am Weiterarbeiten gehindert (durch einen Fehler), so wird die Applikation mittels Milchglas gesperrt. In diesem Fall kann auch die Notification nicht weggeklickt werden (das 'X' wird dann nicht angezeigt).


## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Default

### 4.1 Bestätigung
![Darstellung der Komponente Benachrichtigung in der Ausprägung Bestätigung](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/notification/images/notification_confirmation.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/RLyo3x#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/notification)

### 4.2 Hinweis
![Darstellung der Komponente Benachrichtigung in der Ausprägung Hinweis](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/notification/images/notification_information.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/1wVPln#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/notification)

### 4.3 Warnung 
![Darstellung der Komponente Benachrichtigung in der Ausprägung Warnung](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/notification/images/notification_warning.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/pqYK5G#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/notification)

### 4.4 Fehler 
![Darstellung der Komponente Benachrichtigung in der Ausprägung Fehler](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/notification/images/notification_error.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/VPEo8A#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/notification)

### 4.5 Fehler mit Sprungmarke 
![Darstellung der Komponente Benachrichtigung in der Ausprägung Fehler mit Sprungmarke](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/notification/images/notification_link.png 'class: image')

* Kann ein Fehler nicht einem einzelnen Element zugewiesen werden, dann wird die Fehlermeldung mit Sprungmarken eingesetzt.
* Die einzelnen Sprungmarken werden durch ein «/» getrennt.
* Beim Klick auf eine Sprungmarke wird direkt zum Ursprung des entsprechenden Fehlers gescrollt.
* Das Sprungmarkenziel ist immer auf derselben Seite wie die Notification (kein Absprung auf andere Seiten).

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/YzZ58m#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/notification)


### 4.6 Notification Toast
* Benachrichtigungen können einerseits direkt innerhalb des Contentbereichs angezeigt werden (z.B. aufgrund einer Form-Validierung). Für Benachrichtigungen können aber auch "einfliegende" Toasts verwendet werden.
* Die Anzeigedauer bis zum automatischen Verschwinden kann jetzt nach Anwendungsfall definiert werden. Dahingehend können Toasts auch konfiguriert werden, dass sie nicht automatisch verschwinden.

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/notification-toast)