## 1. What does the component do?
* It is used for the entry of text and numbers.


## 2. When should the component be used?
* When an entry is required from the user.


## 3. Rules 
* An entry field always has a label.
* A question mark in the circle can also be shown – in addition to the label – for detailed explanations. A [tooltip](https://digital.sbb.ch/en/webapps/components/tooltip) opens when this question mark is clicked on.
* The entry text is always single-line.
* If the text becomes longer than the width of the entry field during the entry, the text entered is pushed to the left so that what is currently being written can always be seen.
* After leaving the entry field with a long text, this is cut off at the end and designated with “…”.
* An entry field can contain a placeholder which is shown directly in the entry field provided no value has been entered by the user.
* If the user can never edit a form field, no entry field can be used (display as text).


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
![Image of the text field component in the standard variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/textfield/images/Textfield_Default.png 'class: image')

#### Design specification
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/Pw1oL8#Inspector)
* [Placeholder](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/gk1ZRj#Inspector)
* [Focused](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/8jVpv8#Inspector)
* [Disabled](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/2q7erA#Inspector)
* [Error](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/MVmMa7#Inspector)
* [Mandatory](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/5ynozd#Inspector)
* [Readonly](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/AxL1rj4#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/field)

### 4.2 Password entry
![Image of the text field component in the password entry variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/textfield/images/textfield_password.png 'class: image')
* The entry field in the ‘password’ variant does not provide a ‘Placeholder’ status.

#### Design specification
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/bDLaWj#Inspector)
* [Focused](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/WjdnLk#Inspector)
* [Disabled](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/3Loxjm#Inspector)
* [Error](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/r79reA#Inspector)

### 4.3 Clearable
![Image of the text field component with possibility to clear the value by one click](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/textfield/images/textfield_clearable.png 'class: image')

#### Design spezification
* [Empty](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/zxWKVEo#Inspector)
* [Value](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/ZOlnaWx#Inspector)
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/JnoJxzG#Inspector)
