## 1. What does the component do?
* Structured display of data within a table.


## 2. When should the component be used? 
* It is used for displaying data, not for structuring content.
* Tables should be structured so that they grow vertically (lines) when data sets are added.


## 3. Rules
* Table cells may contain just information (e.g. text, person, status display, icon) or interaction elements (e.g. text field, select, button).
* Every column must have a header (including text or icon).
* Headers can contain subtitles in addition to the title.
* Header and line content may be left-aligned, right-aligned or centred within the table cell: Text left-aligned, icons centred, numbers right-aligned
* Units of measurement in content are ideally entered on the second line of the column header. Alternatively, they can appear directly next to the column header name in round brackets.
* Horizontal scrolling should be avoided as far as possible.
* Columns can be put into logical groups. There is no dividing line between grouped columns.


## 4. Variants and statuses
The component has the following statuses:
* Default
* Hover
* Active

### 4.1 Standard
![Image of the table component in the standard variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/table/images/Table_Default.png 'class: image')

#### Design specification
* [Default](https://www.sketch.com/s/36ab4f9f-f7f8-436e-9d7e-0f2088e52e04/a/L0b3V3y#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/table)

### 4.2 Sortable
This variant has the following statuses:
* Unsorted
* Sorted

![Image of the table component in the variant sortable](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/table/images/Table_Sortable.png 'class: image')

#### Design specification
* [Default](https://www.sketch.com/s/36ab4f9f-f7f8-436e-9d7e-0f2088e52e04/a/7yV3j3Y#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/table)

### 4.3 Groupable
![Image of the table component in the variant groupable](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/table/images/Table_Groupable.png 'class: image')

#### Design specification
* [Default](https://www.sketch.com/s/36ab4f9f-f7f8-436e-9d7e-0f2088e52e04/a/ygLDjDq#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/table)

### 4.4 Selectable
This variant has the following statuses:
* Unselected
* EntrySelected
* AllSelected

![Image of the table component in the variant selectable](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/table/images/Table_Selectable.png 'class: image')

#### Design specification
* [Default](https://www.sketch.com/s/36ab4f9f-f7f8-436e-9d7e-0f2088e52e04/a/9P53z3p#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/table)

### 4.5 Filterable
This variant has the following statuses:
* Unfiltered
* Filtered

![Image of the table component in the variant filterable](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/table/images/Table_Filterable.png 'class: image')

* The individual columns can be filtered according to content type (text, date, value, etc.) using the appropriate components.
* A separate [filter](https://digital.sbb.ch/en/webapps/modules/filter) can also be used to restrict large amounts of data.

#### Design specification
* [Default](https://www.sketch.com/s/36ab4f9f-f7f8-436e-9d7e-0f2088e52e04/a/PGRjqjP#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/table)

### 4.6 Inline actions
![Image of the table component in the variant with inline actions](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/table/images/Table_Actions.png 'class: image')

* When hovering over lines, actions can be offered on the elements.
* The actions are offered by using [icon button](https://digital.sbb.ch/en/webapps/components/button). They are arranged on the far right of the table and overlay the last column.
* A maximum of 3 actions should be offered. If more are needed, a [contextmenu](https://digital.sbb.ch/en/webapps/components/contextmenu) should be used.

#### Design specification
* [Default](https://www.sketch.com/s/36ab4f9f-f7f8-436e-9d7e-0f2088e52e04/a/g07K3Ka#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/business/components/table)
