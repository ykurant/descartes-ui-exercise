# UI Test Assignment

## Instructions
Build an Ember App which displays a list of tariffs. You should use the data found in `​sample-data.js`. Image `component.png` serves as a visual guidance for the expected result.

### App Requirements
* Use Ember.js (`v4.x` or `v3.x`)
* options around data are of your choice, e.g. `ember-data`
* 3rd party addons are of your choice
* for styling use utility based framework, or SASS, or plain CSS

Should be clear instructions on how to run the app.

Please provide a download link of your git repository.

### Functionality Requirements
* The `select-all` checkbox should be in an unselected state if no tariffs are selected.
* The `select-all` checkbox should be in a selected state if all tariffs are selected.
* The `select-all` checkbox should be in an indeterminate state if some but not all tariffs are selected.
* The **Selected 2** text should reflect the count of 2 selected tariffs and display **None Selected** when there are none selected.
* Clicking the `select-all` checkbox should select all tariffs if none or some are selected.
* Clicking the `select-all` checkbox should deselect all tariffs if all are currently selected.
* `schedulesCount`​ in the **Schedules** column should be correctly formatted.
* Clicking **[+]** button in **Schedules** column for zero schedules should show an alert box with the tariff id and supplier name.
* Only those that have a ​`schedulesCount​` of zero can be deleted. Your implementation should manage this.
* Clicking **Delete** button when some or all tariffs are selected should generate an alert box with the tariff id and supplier name of all selected for deletion.
* Precise / exact HTML formatting / styling to match the mockup is not required however rows should change colour when selected and on hover.

Not a part of actual coding assignment, but should be layed out in a form of bullet points or a short thesis:
* Suggest a solution how this app may support multiple tenants, considering each tenant has its own variant of template (e.g. additional columns, different header names, some tenants need **Edit/Delete** option, some don't).