## 1. Was macht die Komponente?
* Dient zur Eingabe eines Datums.


## 2. Wann soll die Komponente eingesetzt werden?
* Immer wenn von den Benutzer*innen ein Datumswert verlangt wird.


## 3. Regeln
* Datumsangaben sind immer einzeilig.
* Die Datumswahl hat immer ein Label.
* Für detaillierte Erklärungen kann neben dem Label ein Fragezeichen im Kreis dargestellt werden. Beim Klick auf dieses Fragezeichen öffnet sich ein [Tooltip](https://digital.sbb.ch/de/webapps/components/tooltip).
* Mit Klick ins Datumsfeld kann das Datum von Hand eingetragen werden.
    * Bei der manuellen Eingabe werden folgende Eingaben ermöglicht, welche von der Komponente automatisch korrekt formatiert werden (Bsp. 1. Januar 2020):
        * '010120'
        * '1.1.20'
        * '01.01.20'
* Bei Klick auf das Kalender-Icon öffnet sich ein Kalender-Layer zur Auswahl des Datums. Mittels Klick ausserhalb des Kalender-Layers wird dieser wieder geschlossen.
* Im Kalender-Layer können einzelne Tage oder ganze Datumsbereiche deaktiviert werden.
* Die Navigationspfeile im Kalender-Layer (Monat / Jahr) werden nur dargestellt, wenn auch ein vorangehendes/nachfolgende Datum gewählt werden kann.
* Wenn der Fokus im Kalender-Layer liegt, kann dieser wie folgt mittels Tastatur bedient  werden:
    * Pfeiltasten: Wechseln des markierten Tages.
    * Leertaste / Enter: Auswahl des markierten Tages.
* Das gewählte Datum wird in der Regel im Format "Wochentag, TT.MM.JJJJ" dargestellt (Beispiel "Fr, 04.08.2017"). Die Anzeige des Wochentags ist dabei optional.


## 4. Ausprägungen und Zustände 
Die Komponente hat folgende Zustände:
* Default
* Placeholder
* Focused
* Disabled
* Error
* Mandatory
* Readonly

### 4.1 Standard
![Darstellung der Komponente Datumsauswahl in der Standard Ausprägung](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/datepicker/images/Dateinput_Default.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/QqD1rL#Inspector)
* [Placeholder](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/jggqqgm#Inspector)
* [Focused](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/xz0QdJ#Inspector)
* [Disabled](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/EAeG9d#Inspector)
* [Error](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/j14rDm#Inspector)
* [Mandatory](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/dllqqlL#Inspector)
* [Readonly](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/jgq7qy0#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/datepicker)

### 4.2 Mit Blätterfunktion
![Darstellung der Komponente Datumsauswahl mit Blätterfunktion](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/datepicker/images/Dateinput_Pageable.png 'class: image')
* Die Navigationspfeile werden nur dargestellt, wenn auch ein vorangehendes/nachfolgende Datum gewählt werden kann.

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/dAgjvL#Inspector)
* [Placeholder](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/zxxOOxM#Inspector)
* [Focused](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/zJyKZM#Inspector)
* [Disabled](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/ZZVnR3#Inspector)
* [Error](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/JRAJrk#Inspector)
* [Mandatory](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/ZOO55O3#Inspector)
* [Readonly](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/dlq0qEZ#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/datepicker)

### 4.3 Datumsbereich
* Um einen Datumsbereich zu wählen, werden zwei Datepicker kombiniert.
* Wird das Von-Datum mittels Kalender-Layer gewählt und das Bis-Datum ist noch nicht definiert, öffnet sich der Kalender-Layer des Bis-Feldes. Wurde bereits ein Bis-Datum gewählt, öffnet sich der Kalender-Layer nicht.
* Wählen die Benutzer*innen ein Von-Datum > Bis-Datum, wird das Bis-Datum gelöscht und dessen Kalender-Layer eingeblendet.
* Sind beide Daten gewählt, wird im Kalender der gewählte Bereich farblich hinterlegt.

### 4.4 Geburtsdatum
![Darstellung der Komponente Datumsauswahl zur Eingabe eines Geburtstages](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/datepicker/images/Dateinput_Birthdate.png 'class: image')

#### Design Spezifikation
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/vjRQy4#Inspector)
* [Placeholder](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/47o5vD#Inspector)
* [Focused](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/e0ld4P#Inspector)
* [Disabled](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/GlodxO#Inspector)
* [Error](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/OKeR8m#Inspector)
* [Mandatory](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/Jnnppnk#Inspector)
* [Readonly](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/zxO7OYW#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/datepicker)

### 4.5 Kalender-Layer (Datepicker)
![Darstellung der Komponente Datumsauswahl mit Kalenderdarstellung](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/datepicker/images/Dateinput_Picker.png 'class: image')
Die Tab-Reihenfolge innerhalb des Kalender-Layers ist wie folgt defniert:
1. Monat zurück
2. Monat vor
3. Jahr zurück
4. Jahr vor
5. Bereich der einzelnen Tage. Wenn der Fokus im Bereich der Tage liegt, kann mittels Pfeiltasten links, rechts, auf und ab innerhalb der Tage navigiert werden.

#### Design Spezifikation
* [Keine Auswahl](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/mYPKWP#Inspector)
* [Datum gewählt](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/DaEwY4#Inspector)
* [Datum mit Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/j14rQb#Inspector)
* [Auswahleinschränkungen](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/dAgjmj#Inspector)
* [Datumsbereich innerhalb eines Monats](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/zJyK3l#Inspector)
* [Datumsbereich über Monatsgrenze](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/ZZVnjv#Inspector)

#### Code Spezifikation
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/datepicker)
