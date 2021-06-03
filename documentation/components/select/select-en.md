## 1. What does the component do? 
* It is used for the selection of one or more options from a pre-defined list.


## 2. When should the component be used?
* For the selection of several options (selection of single or multiple options) from a list.
* If a selection must be made where the entries mutually exclude one another and no default value is to be set (in contrast to the [radio button](https://digital.sbb.ch/en/webapps/components/radiobutton) element.
* When selection options are to be grouped.


## 3. Rules
* There must be a choice of at least two options.
* The element always has a label.
* A question mark in the circle can also be shown – in addition to the label – for detailed explanations. A [tooltip](https://digital.sbb.ch/en/webapps/components/tooltip) opens when this question mark is clicked on.
* The text in the select element is always single-line.
* If an entry is longer than the available width of the element, the entry’s text is abbreviated with ‘…’.
* A pre-selection is not permitted with a mandatory field.
* If no selection has been made yet, the element text says “please select …”.


## 4. Variants and statuses
The component has the following statuses:
* Default
* Hinted
* Focused
* Disabled
* Error
* Mandatory
* Expanded

### 4.1 Standard
![Image of the select component in the standard variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/select/images/Select_Default.png 'class: image')

#### Design specification
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/5ynoRd#Inspector)
* [Hinted](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/v88vv84#Inspector)
* [Focused](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/bDLaGj#Inspector)
* [Disabled](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/Wjdn2k#Inspector)
* [Error](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/3LoxWm#Inspector)
* [Mandatory](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/4aabbaD#Inspector)
* [Expanded](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/r79r5A#Inspector)
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/nKQDZl#Inspector)
* [Active](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/QqD1Mb#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/select)

### 4.2 Multiple choice 
![Image of the select component with multiple choice](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/select/images/select_multi.png 'class: image')

#### Design specification
* [Collapsed](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/xz0QA0#Inspector)
* [Expanded](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/EAeGJq#Inspector)
* [Expanded Autocomplete](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/j14rpb#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/select)

### 4.3 Grouped single choice
![Image of the select component with grouped entries](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/select/images/Select_Grouped_Single.png 'class: image')

#### Design specification
* [Expanded](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/dAgjMj#Inspector)
* [Expanded Tree](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/m4Ye4w#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/select)

### 4.4 Grouped multiple choice
![Image of the select component with grouped entries and multiple choice](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/select/images/Select_Grouped_Multi.png 'class: image')

#### Design specification
* [Expanded](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/zJyK5l#Inspector)
* [Expanded Tree Checkbox](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/ZZVnLv#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/select)
