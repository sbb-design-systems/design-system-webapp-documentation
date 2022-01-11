## 1. What does the component do?
* It is used for the entry of a date.


## 2. When should the component be used?
* Whenever a date value is required from the user.


## 3. Rules    
* Date details are always single-line.
* The date selection always has a label.
* A question mark in the circle – in addition to the label – can be used for detailed explanations. A [tooltip](https://digital.sbb.ch/en/webapps/components/tooltip) opens when clicking on this question mark.
* The date can be entered by hand by clicking in the date field.
    * Manual entry allows the following entries, which are automatically formatted correctly by the component (e.g. 1 January 2020):
        * '010120'
        * '1.1.20'
        * '01.01.20'
* When the calendar icon is clicked on, a calendar layer opens to select the date. Clicking outside of the calendar layer closes it again.
* Individual days or entire date ranges can be deactivated in the calendar layer.
* The navigation arrows in the calendar layer (month/year) are only shown if a preceding/subsequent date can be selected.
* If the focus is on the calendar layer, it can be operated by keyboard as follows:
    * Arrow keys: Changing the marked day.
    * Space key / Enter: Selection of the marked day.
* The selected date is usually displayed in the format "Weekday, DD.MM.YYYY" (example "Fr, 04.08.2017"). The display of the weekday is optional.


## 4. Variants and statuses
The component has the following statuses:
* Default
* Placeholder
* Focused
* Disabled
* Error
* Mandatory
* Readonly

### 4.1 Standard
![Image of the date selection component in the standard variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/datepicker/images/Dateinput_Default.png 'class: image')

#### Design specification
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/QqD1rL#Inspector)
* [Placeholder](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/jggqqgm#Inspector)
* [Focused](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/xz0QdJ#Inspector)
* [Disabled](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/EAeG9d#Inspector)
* [Error](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/j14rDm#Inspector)
* [Mandatory](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/dllqqlL#Inspector)
* [Readonly](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/jgq7qy0#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/datepicker)


### 4.2 With scroll function
![Image of the date selection component with scroll function](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/datepicker/images/Dateinput_Pageable.png 'class: image')
* The navigation arrows are only shown if a preceding/subsequent date can be selected.

#### Design specification
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/dAgjvL#Inspector)
* [Placeholder](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/zxxOOxM#Inspector)
* [Focused](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/zJyKZM#Inspector)
* [Disabled](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/ZZVnR3#Inspector)
* [Error](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/JRAJrk#Inspector)
* [Mandatory](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/ZOO55O3#Inspector)
* [Readonly](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/dlq0qEZ#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/datepicker)

### 4.3 Date range
* Two date pickers are combined to select a date range.
* If the from date is selected via the calendar layer and the to date has not yet been defined, the calendar layer of the to field opens. If a to date has already been selected, the calendar layer does not open.
* If the user selects a from date > to date, the to date is deleted and its calendar layer is shown.
* If both dates are shown, the selected range is entered in the calendar in colour.

### 4.4 Date of birth
![Image of the date selection component for entry of a date of birth](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/datepicker/images/Dateinput_Birthdate.png 'class: image')

#### Design specification
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/vjRQy4#Inspector)
* [Placeholder](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/47o5vD#Inspector)
* [Focused](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/e0ld4P#Inspector)
* [Disabled](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/GlodxO#Inspector)
* [Error](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/OKeR8m#Inspector)
* [Mandatory](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/Jnnppnk#Inspector)
* [Readonly](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/zxO7OYW#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/datepicker)

### 4.5 Calender Layer (date picker)
![Image of the date selection component with date picker](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/datepicker/images/Dateinput_Picker.png 'class: image')
The tab sequence within the calender layer is defined as follows:
1. Previous month
2. Next month
3. Previous year
4. Next year
5. range of the individual days. If the focus is on the range of days, it is possible to navigate left, right, up and down within the days using the arrow keys.

#### Design specification
* [No selection](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/mYPKWP#Inspector)
* [Date selected](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/DaEwY4#Inspector)
* [Date with hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/j14rQb#Inspector)
* [Selection restrictions](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/dAgjmj#Inspector)
* [Date range within a month](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/zJyK3l#Inspector)
* [Date range beyond a month](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/ZZVnjv#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/datepicker)