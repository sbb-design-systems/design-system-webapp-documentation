## 1. What does the component do?
* It is used to structure the display of data and forms.


## 2. When should the component be used? 
* For switching between various aspects within the same context.
* When the content of various aspects cannot be seen at the same time by the user.


## 3. Rules
* The first tab is always selected by default.
* The tab names are always single-line.
* The tab name should be as simple and concise as possible so that the themes can be quickly understood.
* If the tab is too long for the viewport, the width is shortened and the names are shortened with “…”. When hovering over the tab, the complete name appears in a [tooltip](https://digital.sbb.ch/en/webapps/components/tooltip).
* Another tab module is not permitted within a tab (tab-in-tab).


## 4. Variants and statuses
The component has the following statuses:
* Active
* Inactive
* Hover
* Disabled

### 4.1 Standard
![Image of the tab component](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/tab/images/tab_default.png 'class: image')

#### Design specification
* [Active](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/47o5dx#Inspector)
* [Inactive](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/e0ldMz#Inspector)
* [Hover](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/Glod4Y#Inspector)
* [Disabled](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/OKeRL8#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/tabs?variant=lean)