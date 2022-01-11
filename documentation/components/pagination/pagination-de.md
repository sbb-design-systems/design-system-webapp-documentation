## 1. Was macht die Komponente?
* Blättert durch eine Liste von Elementen oder Seiten.


## 2. Wann soll die Komponente eingesetzt werden?
* Bei langen Listen von Elementen oder Seiten.


## 3. Regeln
* Anzahl Elemente pro Seite muss kontextspezifisch definiert werden.
* Maximal 5 Seitenzahlen werden angezeigt.
* Tastaturbedienung
    * Die aktive Seite kann nicht angesprungen werden.
	* Tab-Reihenfolge: Pfeil zurück, erste anspringbare Seite, nächste anspringbare Seite usw., Pfeil vorwärts.
	*  Die Kurzform «...» für versteckte Seiten kann nicht angesprungen werden.


## 4. Ausprägungen und Zustände
Die Komponente hat folgende Zustände:
* First
* Middle
* Last
* Hover

### 4.1 Standard
![Darstellung der Komponente Seitennummerierung](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/pagination/images/pagination_default.png 'class: image')

#### Design Spezifikation
* [First](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/K10Rwg#Inspector)
* [Middle](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/wd5QMq#Inspector)
* [Last](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/qLbV52#Inspector)
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/Lp4n13#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/pagination?variant=lean)