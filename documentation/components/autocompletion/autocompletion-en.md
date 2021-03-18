## 1. What does the component do?
* It helps the user with entry by providing suggestions.


## 2. When should the component be used?
* When an entry field can have lots of pre-defined values.
* As a tool for previewing search results/fields.


## 3. Rules
* The auto-completion always has a label.
* Optional entries include the text ‘(optional)’ behind the label text. The text ‘(optional)’ can be shortened to ‘(opt.)’ in short fields.
* A question mark in the circle – in addition to the label – can be used for detailed explanations. A [tooltip](https://digital.sbb.ch/en/webapps/components/tooltip) opens if this question mark is clicked on.
* During entry three suggestions appear (usually after three symbols but this can be modified on a project-specific basis).
* The listed entries can be scrolled through using arrow keys and accepted with ‘Enter’.
* A maximum of ten suggestions are shown.
* The auto-completion selection closes when an element is chosen.


## 4. Variants and statuses
The component has the following statuses:
* Default
* Hover
* Active

### 4.1 Standard
![Image of the autocomplete component in the standard variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/autocompletion/images/autocompletion_default.png 'class: image')

#### Design specification
*   [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/8jVp57#Inspector)
*   [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/2q7ekM#Inspector)
*   [Active](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/MVmMnw#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/autocomplete)

### 4.2 With hit display
As an option to the standard variant, this variant can be used when an auto-completion list always contains more than the maximum ten hits shown.
![Image of the autocompletion component with display of hits](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/autocompletion/images/Autocompletion_Overflow.png 'class: image')

#### Design specification
*   [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/5ynoWw#Inspector)
*   [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/bDLaKJ#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/autocomplete)

### 4.3 With static entries
![Image of the autocompletion component with static entries](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/autocompletion/images/Autocompletion_Static.png 'class: image')

#### Design specification
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/Wjdn3y#Inspector)
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/3LoxEr#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/autocomplete)
