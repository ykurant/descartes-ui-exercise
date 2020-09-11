# UI Exercise

## Instructions

### Ember.js
Use Ember.js, options around data are your choice e.g. you can opt to use ember data if you choose.  For CSS, utility based framework or plain CSS would be good.  Please provide a download link of your git repository.

### Non-specific framework/lib
Use framework/lib of your choice.  Should be clear instructions on how to run.  For CSS, utility-based framework or plain CSS would be good.  Please provide a download link of your git repository.

----

This component displays a list of tariffs which can be deleted. You should use the data found in ​sample-data.js

## Requirements

* Only those that have a ​schedulesCount​ of zero can be deleted. Your implementation should manage this.
* The select-all checkbox should be in an unselected state if no tariffs are selected.
* The select-all checkbox should be in a selected state if all tariffs are selected.
* The select-all checkbox should be in an indeterminate state if some but not all tariffs
are selected.
* The "Selected 2" text should reflect the count of selected tariffs and display "None
Selected" when there are none selected.
* Clicking the select-all checkbox should select all tariffs if none or some are selected.
* Clicking the select-all checkbox should deselect all tariffs if all are currently selected.
* schedulesCount​ in the Schedules column should be correctly formatted.
* Clicking the ​schedulesCount​ [+] button for zero schedules should show an alert box
with the tariff id and supplier name.
* Clicking "Delete" when some or all tariffs are selected should generate an alert box
with the tariff id and supplier name of all selected for deletion.
* Precise / exact HTML formatting / styling to match the mockup is not required
however rows should change colour when selected and on hover.
