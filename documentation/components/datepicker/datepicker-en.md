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
* Focused
* Disabled
* Error

### 4.1 Standard
![Image of the date selection component in the standard variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/datepicker/images/dateinput_default.png 'class: image')

#### Design specification
* [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355318424/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/17140415/355318425/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/17140415/355318426/inspect)
* [Error](https://sbb.invisionapp.com/d/main#/console/17140415/355318427/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/datepicker)


### 4.2 With scroll function
![Image of the date selection component with scroll function](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/datepicker/images/dateinput_pageable.png 'class: image')
* The navigation arrows are only shown if a preceding/subsequent date can be selected.

#### Design specification
* [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355318428/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/17140415/355318429/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/17140415/355318430/inspect)
* [Error](https://sbb.invisionapp.com/d/main#/console/17140415/355318431/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/datepicker)

### 4.3 Date range
* Two date pickers are combined to select a date range.
* If the from date is selected via the calendar layer and the to date has not yet been defined, the calendar layer of the to field opens. If a to date has already been selected, the calendar layer does not open.
* If the user selects a from date > to date, the to date is deleted and its calendar layer is shown.
* If both dates are shown, the selected range is entered in the calendar in colour.

### 4.4 Date of birth
![Image of the date selection component for entry of a date of birth](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/datepicker/images/dateinput_birthdate.png 'class: image')

#### Design specification
* [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355318432/inspect)
* [Hinted](https://sbb.invisionapp.com/d/main#/console/17140415/355318433/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/17140415/355318434/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/17140415/355318435/inspect)
* [Error](https://sbb.invisionapp.com/d/main#/console/17140415/355318436/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/datepicker)

### 4.5 Calender Layer (date picker)
![Image of the date selection component with date picker](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/datepicker/images/Dateinput_Picker.png 'class: image')
The tab sequence within the calender layer is defined as follows:
1. Previous month
2. Next month
3. Previous year
4. Next year
5. range of the individual days. If the focus is on the range of days, it is possible to navigate left, right, up and down within the days using the arrow keys.

#### Design specification
* [No selection](https://sbb.invisionapp.com/d/main#/console/17140415/355318437/inspect)
* [Date selected](https://sbb.invisionapp.com/d/main#/console/17140415/355318438/inspect)
* [Date with hover](https://sbb.invisionapp.com/d/main#/console/17140415/355318439/inspect)
* [Selection restrictions](https://sbb.invisionapp.com/d/main#/console/17140415/355318440/inspect)
* [Date range within a month](https://sbb.invisionapp.com/d/main#/console/17140415/355318441/inspect)
* [Date range beyond a month](https://sbb.invisionapp.com/d/main#/console/17140415/355318442/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/datepicker)
