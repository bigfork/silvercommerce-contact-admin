# Log of changes for Orders Admin module

## 1.0.0

* First initial release

## 1.0.1

* Fix error when using default location on a contact.

## 1.0.2

* Add additional extension hooks to model classes

## 1.0.3

* Clean up permissions and add can functions to notes

## 1.0.4

* Ensure associations are removed from the DB on contact deletion

## 1.0.5

* Switch bulk editing dependency 

## 1.0.6

* Add ability to bulk assign tags to contacts
* Add bulk editing fields to tags and lists 

## 1.1.0

* Update to work with latest bulk manager

## 1.1.1

* Add autocomplete fields for searchform in ContactAdmin
* Some minor code cleanup

## 1.2.0

* Allow associating a `Contact` to a `Member`
* Remove `Salutation` and `Middlename` from a `Contact`
* Add versioning support to a `Contact` and `ContactLocation`

## 1.2.1

* Automatically add region selection field if GeoLocations module is installed
* Hide Version field

## 1.2.2

* Switch top using `ModelAdminPlus`
* Add extension hook to required fields

## 1.2.3

* Remove AutoCompleteFields (this is now managed via `ModelAdminPlus`)

## 1.2.4

* Update bulk actions on tags and lists inline with `BulkHandler`

## 1.2.5

* Fix flagged filter (LT SS4.3)
* Update model docs

## 1.2.6

* Add additional extension hook to validator on ContactLocation

## 1.3.0

* Add improved contact import/export
* Add additional contact permissions

## 1.3.1

* Ensure that only one of each user group is created on build

## 1.3.2

* Change default contact group tag matches what is converted by SilverStripe

## 1.3.3

* Ensure groups are using a compatible code when initially creating.