## 1. What does the component do?
* It is used to display messages that concern an entire page or module of an application.


## 2. When should the component be used?
* If a user has triggered an action on a page and should receive feedback from the system.
* Or if a technical problem exists that prevents the user from working.


## 3. Rules
* Notifications always only appear after an action has been triggered by the user.
* The width can be based on the width of a form, the entire content area or a standard width with use as toast.
* The height is based on the length of the message text.
* If the user is prevented from continuing to work (by an error), the application is blocked by frosted glass. In this case, the notification cannot be clicked away either (the ‘X’ is not then shown).


## 4. Variants and statuses
The component has the following statuses:
* Default

### 4.1 Confirmation
![Image of the message component in the confirmation variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/notification/images/notification_confirmation.png 'class: image')

#### Design specification
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/RLyo3x#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/notification?variant=lean)

### 4.2 Notification
![Image of the message component in the notification variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/notification/images/notification_information.png 'class: image')

#### Design specification
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/1wVPln#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/notification?variant=lean)

### 4.3 Warning 
![Image of the message component in the warning variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/notification/images/notification_warning.png 'class: image')

#### Design specification
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/pqYK5G#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/notification?variant=lean)

### 4.4 Error 
![Image of the message component in the error variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/notification/images/notification_error.png 'class: image')

#### Design specification
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/VPEo8A#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/notification?variant=lean)

### 4.5 Error with jump marker 
![Image of the message component in the error with jump marker variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/notification/images/notification_link.png 'class: image')

* If an error cannot be assigned to an individual element, then the error message with jump marker is used.
* The individual jump markers are separated with a '/'.
* The cause of the error is scrolled to if a jump marker is clicked on.
* The jump marker target is always on the same page as the notification (no jumping to other pages).

#### Design specification
* [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/YzZ58m#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/notification?variant=lean)


### 4.6 Notification Toast
* Notifications can be displayed directly within the content area (e.g. due to form validation). However, "flying in" toasts can also be used for notifications.
* The display duration until automatic disappearance can now be defined according to the use case. To this end, toasts can also be configured not to disappear automatically.

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/notification-toast?variant=lean)