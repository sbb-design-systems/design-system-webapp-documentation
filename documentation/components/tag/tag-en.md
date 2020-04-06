## 1. What does the component do?
It categorises a large amount of information.


## 2. When should the component be used?
* For filtering results with lots of categories.


## 3. Rules
* A tag always has an indicator which shows how many results are behind it.
* The term in the tag is always single-line (no line breaks) and the tag itself increases in width with the text.
* If a tag becomes too long for the viewport due to the text, the text is shortened with «...».


## 4. Variants and statuses
The component has the following statuses:
* Active
* Inactive

### 4.1 Filter tag
![Image of the filter tag component used as filter](https://raw.githubusercontent.com/sbb-design-systems/design-system-webapp-documentation/master/documentation/components/tag/images/tag_filter.png 'class: image')

* In the filter there are tags in status active or inactive.
* When a tag is clicked, the status concerned toggles to the other status and influences the filter result.
* A tag «All» is always inserted within the filter. If this filter tag is clicked, it changes to the active status and all other tags in the filter are set to the inactive status.

#### Design specification
* [Active](https://sbb.invisionapp.com/d/main#/console/17140415/412486708/inspect)
* [Inactive](https://sbb.invisionapp.com/d/main#/console/17140415/412486709/inspect)
