## 1. What does the module do?
* Allows you to filter a large amount of information.


## 2. When should the module be used?
* For restricting large amounts of data by selected categories and attributes.


## 3. Rules
* A filter always has an indicator which shows that the filter is active and how many results are displayed in the filtered view, e.g. 100/500 entries.
* A filter can have different components, e.g. [autocomplete](https://digital.sbb.ch/de/webapps/components/autocomplete), [checkboxes](https://digital.sbb.ch/de/webapps/components/checkbox), [chips](https://digital.sbb.ch/de/webapps/components/chip), [datepicker](https://digital.sbb.ch/de/webapps/components/datepicker), [radio buttons](https://digital.sbb.ch/de/webapps/components/radiobutton), [selects (dropdowns)](https://digital.sbb.ch/de/webapps/components/select), [tags](https://digital.sbb.ch/de/webapps/components/tag), [textfields](https://digital.sbb.ch/de/webapps/components/textfield), [toggle buttons](https://digital.sbb.ch/de/webapps/components/toggle). 
* It must be possible to reset a filter with an action (e.g. button «Reset filter»).
* Several filter elements can be selected or deselected.


## 4. Variants and statuses
The module has the following statuses:
* Filtered
* Not Filtered

## 4.1 Live filter
![Image of a live filter example](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/modules/filter/images/Filter_Live.png 'class: image')

* The live filter contains the most frequently used filter criteria for finding specific information.
* When a filter criterion is changed, the results are updated live in the viewport.

### 4.2 Filter dialog
![Image of a filter dialog example](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/modules/filter/images/Filter_Dialog.png 'class: image')

* The filter dialog is opened by a button or link.
* The filter dialog contains a large number of filter criteria for finding specific information.
* If required, further filter criteria can be added to the dialog to provide additional filter elements.
* Filtering can be confirmed by clicking on «Filtern» (Primary Button) or can be cancelled by clicking on «Abbrechen» (Secondary Button).
* The results are updated in the viewport after confirming the filter criteria in the dialog box.
