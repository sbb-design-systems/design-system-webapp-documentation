## 1. Was macht das Modul?
* Ermöglicht die Filterung einer grossen Anzahl von Informationen.


## 2. Wann soll das Modul eingesetzt werden? 
* Zum Einschränken grosser Datenmengen nach ausgewählten Kategorien und Attributen.


## 3. Regeln
* Ein Filter hat immer einen Indikator, welcher angibt, dass der Filter aktiv ist und wie viele Ergebnisse in der gefilterten Ansicht dargestellt werden, z.B. 100/500 Einträge.
* Ein Filter kann über unterschiedliche Komponenten verfügen, z.B. [Autocomplete](https://digital.sbb.ch/de/webapps/components/autocomplete), [Checkboxen](https://digital.sbb.ch/de/webapps/components/checkbox), [Chips](https://digital.sbb.ch/de/webapps/components/chip), [Datepicker](https://digital.sbb.ch/de/webapps/components/datepicker), [Radiobuttons](https://digital.sbb.ch/de/webapps/components/radiobutton), [Selects (Dropdowns)](https://digital.sbb.ch/de/webapps/components/select), [Tags](https://digital.sbb.ch/de/webapps/components/tag), [Freitextfelder](https://digital.sbb.ch/de/webapps/components/textfield), [Toggle Buttons](https://digital.sbb.ch/de/webapps/components/toggle). 
* Ein Filter muss mit einer Aktion zurückgesetzt werden können (z.B. Button «Filter zurücksetzen»).
* Mehrere Filter-Elemente können ausgewählt oder abgewählt werden.


## 4. Ausprägungen und Zustände
Das Modul hat folgende Zustände:
* Filtered
* Not Filtered

### 4.1 Live Filter
![Darstellung eines Beispiels eines Live Filters](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/modules/filter/images/Filter_Live.png 'class: image')

* Der Live Filter enthält die am häufigsten verwendeten Filterkriterien zum Auffinden bestimmter Informationen.
* Beim Verändern eines Filterkriteriums werden die Ergebnisse im Viewport live aktualisiert.

### 4.2 Filter Dialog
![Darstellung eines Beispiels eines Filter Dialogs](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/modules/filter/images/Filter_Dialog.png 'class: image')

* Der Filter Dialog wird mittels eines Buttons oder Links geöffnet.
* Der Filter Dialog enthält eine grosse Anzahl an Filterkriterien zum Auffinden bestimmter Informationen. 
* Bei Bedarf können weitere Filterkriterien zum Einblenden im Dialog untergebracht werden, um zusätzliche Filter-Elemente zur Verfügung zu stellen.
* Die Filterung kann mittels «Filtern» (Primary Button) bestätigt oder mittels «Abbrechen» (Secondary Button) abgebrochen werden.
* Die Ergebnisse werden nach der Bestätigung der Filterkriterien im Dialogfenster im Viewport aktualisiert.
