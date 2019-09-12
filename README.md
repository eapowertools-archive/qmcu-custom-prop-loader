# Status
[![Project Status: Unsupported – The project has reached a stable, usable state but the author(s) have ceased all work on it. A new maintainer may be desired.](https://www.repostatus.org/badges/latest/unsupported.svg)](https://www.repostatus.org/#unsupported)

# qmcu-custom-prop-loader

## What it does
The Custom Property Bulk Loader facilitates the creation and update of custom properties using a csv file to populate custom property values.

## How it works
The Custom Property Bulk Loader is made to resemble the custom property page in the Qlik Sense QMC.  However, it has one key difference; the ability to upload a csv file containing the values for the custom property.

![1](https://s3.amazonaws.com/eapowertools/qmcutilities/CustomPropLoader.png)

1. With the bulk loader, the user picks an existing custom property to update, or enters a name in the text box to create a new custom property.
2. Select the resources the custom property will apply to just like in the QMC page.
3. Select a csv file containing a single column list of values without a header. Click the upload button to see the list of custom property values that will be inserted.
4. Click the Create or Update buttons (one or the other will appear).

The custom property bulk loader is a great solution for adding custom properties used for dynamic security rules where custom properties on resources are compared against user attributes imported through user directory connectors or session attributes.  It saves administrators time because they don't have to add values manually one by one to the existing custom property interface in the QMC.
