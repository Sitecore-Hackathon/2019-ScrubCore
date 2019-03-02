# Bulk Field Editor Documentation

## Summary

**Category:** Best use of SPE to help Content authors and Marketers

The purpose of our module is to enable a content editor to quickly and easily edit multiple items simultaneously. With the Bulk Field Editor a content editor can walk through a few easy to understand steps to select the type of item, the fields to edit, and the specific items to make changes too. The Editor can be easily accessed right from the content editor from a ribbon button. 

## Pre-requisites

 - Sitecore Powershell Extensions Version 5.0 (Full 5.0 Release)
	 - The SPE 5.0 sitecore package should be installed prior to installing the Bulk Field Editor

## Installation

1. Ensure that Sitecore Powershell Extensions Version 5.0 (Full 5.0 Release) is installed
2. Simply use the Sitecore Installation wizard to install the [package](../sc.package/Bulk%20Field%20Editor-1.0.zip)
3. You're ready to edit and the Bulk Edit button should appear in the ribbon on the home tab.

## Configuration

The Bulk Field Editor is ready to use immediately after installation, no configuration required.

## Usage

 1. Navigate to the desired root item. This will allow you to edit any of this item’s sub-items. Then select the Home tab and click the Bulk Edit button in the Edit chunk.

![itemA.png](images/itemA.png?raw=true "itemA.png")

 2. You will be prompted to select a template from the available list of templates that exist under your selected root item. Templates with no editable fields will not be displayed. Select the template for the type of items you wish to edit and click OK.

![itemB.png](images/itemB.png?raw=true "itemB.png")

 3. You will then be offered the option to select and edit *all* sub-items with this template.
	 a. Leave this checkbox unchecked and select OK if you would like to select specific items to edit. Proceed to Step 4 to choose your items.
	 b. Check this checkbox and select OK if you would like to make edits to *all* of the sub-items with your selected template. Proceed to step 5.

![itemC.png](images/itemC.png?raw=true "itemC.png")

 4. If you opted to select specific items to edit in step 3, you will be presented with a treelist field where you can select the items that you would like to edit. You will only be allowed to select items with the template that you specified in step 2. Select your items by selecting them in the left window and clicking the right arrow to add them to the right window. Once you have selected all of your desired items, click OK.

![itemD.png](images/itemD.png?raw=true "itemD.png") 

 5. On the next screen you will be presented with a set of checkbox lists. These are all of your editable fields separated into their field sections. You may check the checkboxes of any of the fields you wish to edit at this time. Once you are done, click OK to continue.

![itemE.png](images/itemE.png?raw=true "itemE.png") 

 6. You will be provided with a final warning that your selected fields will be wiped out and populated with new information. Press OK to continue or Cancel to exist the process and start over.

![itemF.png](images/itemF.png?raw=true "itemF.png") 

 7. If you opted to continue by selecting OK, you will have the opportunity to make the edits to your selected fields. Edit these fields as you would on a normal Sitecore item and select OK when you are finished. Your changes will be applied to all of your selected items.

![itemG.png](images/itemG.png?raw=true "itemG.png") 

 8. Once the script is done running, click Close to exist the window.

![itemH.png](images/itemH.png?raw=true "itemH.png") 

## Video

[![Bulk Field Editor Sitecore Hackathon](https://img.youtube.com/vi/pGJ1-g-LbVg/0.jpg)](https://youtu.be/pGJ1-g-LbVg)
