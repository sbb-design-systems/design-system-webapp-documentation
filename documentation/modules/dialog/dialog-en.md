## 1. What does the module do?
* Causes an action by the user for specific decisions.


## 2. When should the module be used?
* When an action has to be confirmed by the user.
* To display critical information that has to be confirmed by the user.
* To request actions that has to be confirmed by the user.
* To select decision options by the user.


## 3. Rules
* ...
### 3.1 Behaviour
* Dialogs are displayed as modal windows in front of the application.
* Dialogs disable all application functions and remain displayed until they have been confirmed, cancelled or a necessary action has been performed.
* Dialogs are purposefully interruptive, so they should be used sparingly.
* The dialog can be closed and thus the action cancelled in several ways:
    * via the 'X' on the right in the header of the dialog.
    * via a click on the 'glass' in the background
    * via a 'Cancel'-button (if available)
    * 'ESC' key on the keyboard

### 3.2 Layout
* The dialog has its own header, content area and button bar.
* It should be prevented from scrolling. If it cannot be prevented, the header and button bar are sticky.
* The primary action is placed to the left of the secondary action.
* A 'glass' is displayed behind the dialog, thus blocking editing outside the dialog.

### 3.3 Content
* The header may contain context-describing information (e.g. the train number).
* The content of the dialog can be used completely flexibly, e.g.
    * a detailed description of the situation and a clear question to be answered by the user.
    * a form to create or edit a complex data object.

### 3.4 Actions
* Confirmation actions are disabled until a selection is made or the form is valid (all mandatory fields filled and no incorrect entries).
* Cancel actions are never disabled.


## 4. Variants and statuses
## 4.1 Simple (Warnings / Confirmations)
This variant has following statuses:
* Default

![Image of the dialog module in the simple variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/modules/dialog/images/Dialog_Simple.png 'class: image')

#### Design specification
* [Default](https://www.sketch.com/s/36ab4f9f-f7f8-436e-9d7e-0f2088e52e04/a/gkVMoM#Inspector)
* Glass: [Default](https://www.sketch.com/s/58b25e4c-bf9c-4f74-973f-503538fcbea2/a/vjRQvb#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/dialog)

### 4.2 Complex (Formulare)
This variant has following statuses:
* Valid
* Not Valid

![Image of the dialog module in the complex variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/modules/dialog/images/Dialog_Complex.png 'class: image')

* The complex variant is used to create or edit complex data objects if they cannot be edited directly in the content of the application.
* If the user wants to dismiss the dialog and ...
    * no changes have been made, the dialog closes and no discard confirmation is required.
    * the user has made changes, the user is prompted to confirm the discard action.

#### Design specification
* [Valid / Not Valid](https://www.sketch.com/s/36ab4f9f-f7f8-436e-9d7e-0f2088e52e04/a/ZOW5MWJ#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/dialog)
