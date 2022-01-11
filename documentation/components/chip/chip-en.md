## 1. What does the component do?
* It shows values and categories as compact elements.


## 2. When should the component be used?
* When it should be possible to assign several values to an attribute in a form.
* For filtering by categories.


## 3. Rules
* The term in the chip is always single-line (no line breaks) and the chip itself increases in width with the text.
* If a chip is too long for the viewport because of the text, the text is shortened with “…”.
* The input chips are shown in a [text field](https://digital.sbb.ch/en/webapps/components/textfiled). This can also be multi-line depending on the number of chips and available space.
* The chips in the textfield can be deleted by using backspace.
* The chips can be generated via ‘autocomplete’ selection or with free text depending on the use case.

## 4. Variants and statuses
The component has the following statuses:
* Active
* Disabled
* Hover
* Focused

### 4.1 Input
![Image of the chip component as an entry value](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/chip/images/chip_input.png 'class: image')

#### Design specification
* [Active](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/yZ9QzA#Inspectors)
* [Disabled](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/9dlWmn#Inspector)
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/Pw1onQ#Inspector)
* [Focused](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/gk1ZGz#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/chips?variant=lean)