# mediawiki-pages-DynamicProperties

## Features

* Add/edit/remove properties
  * Add a property to page wikitext source using `{{Property|label|value}}`.
  * Add ***new*** (and typeahead on existing) page properties through [Page Forms](https://www.mediawiki.org/wiki/Extension:Page_Forms)
* View properties
  * Place `{{AnnotationsList}}` on a page to **list that page's own properties**
  * Place `{{AnnotationsList|some other page}}` on a page to **list some other page's properties**

## Background
* PropertyClass: Property,ActiveAction,PassiveAction (#LEX2206031503)