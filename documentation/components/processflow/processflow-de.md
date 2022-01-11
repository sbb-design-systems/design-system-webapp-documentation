## 1. Was macht die Komponente?
* Dient zur Anzeige in welchem Schritt eines Prozesses sich die Benutzer*innen befindet.


## 2. Wann soll die Komponente eingesetzt werden?
* Bei sämtlichen Prozessen bei denen die Benutzer*innen mehrere Schritte/Seiten durchlaufen um diesen abschliessen zu können.


## 3. Regeln
* Der Processflow ist immer zuoberst, direkt nach dem [Breadcrumb](https://digital.sbb.ch/de/webapps/components/breadcrumb) (falls vorhanden) positioniert.
* Die Benutzer*innen können im Processflow auf einen bereits durchlaufenen Prozesschritt zurücknavigieren.
* Vorwärtsnavigation im Prozess ist nur durch den Call-to-Action der entsprechenden Seite erlaubt. Ein Überspringen (vorwärts) von Schritten ist nicht erlaubt.


## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* Default
* Hover

### 4.1 Standard
![Darstellung der Komponente Prozessflow](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/processflow/images/processflow_default.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/7P1axP#Inspector)
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/yZ9QMa#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/processflow)