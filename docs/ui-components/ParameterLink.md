---
layout: default
title: Parameter Link
parent: User Guide
nav_order: 9
---

![DiStem Parameter Link - Easily create links between Instance/Type parameters.](../../)  


# Parameter Link
{: .no_toc }
Parameter Link allows you to create links between parameters, whether Type or Instance, in elements filtered by Disciplines and Categories. 

## Core Features
{: .no_toc }
- Parameter Link allows you to create links between parameters.
- Filter Parameters by Discipline and Categories.
- Add Custom Field and Custom Separator to customize the values of the linked parameters.
- Apply Link to the Whole Model, the Active View or Current Element Selected.
- Save Parameter Link profile.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Add Link

To get started, click on the Add link button to select the Parameters that will be linked and customize the additional settings.

![ParameterLink](../../assets\images\ParameterLink\PL-OpenPlugin.gif)  
<sub>Note: the version on the image may not reflect the [latest version](https://diroots.com/revit-plugins/distem-bundle-for-autodesk-revit/).</sub>

### Firts steps:

1. Enter a custom Link Name or keep the default.

2. In the first dropdown list, select link Type or Instance Parameters.

3. In the second dropdown list, select the Discipline to filter elements.

4. In the last dropdown list, select the element Category.

![Add Link](../../assets\images\ParameterLink\PL-AddLink.gif)  
<sub>Note: the version on the image may not reflect the [latest version](https://diroots.com/revit-plugins/distem-bundle-for-autodesk-revit/).</sub>

### Next steps:

#### Source Field

In the firts table, choose the Source Parameters and use the arrows or double-click to add to the the Selected Parameters table.

- Use the Searchbox to find Parameters.
- Add Cutom Field and Custom Separator to compose the values of the linked parameters.
- Active the default Field Separator to add between the parameter values.

```yaml
#Note:
- User are able to select multiple Source Parameters.
- Note that a preview of the composition of the parameter values is shown below the table of selected parameters.
```

![Source Parameter](../../assets\images\ParameterLink\PL-SourceParameter.gif)  
<sub>Note: the version on the image may not reflect the [latest version](https://diroots.com/revit-plugins/distem-bundle-for-autodesk-revit/).</sub>

#### Target Parameter

Select the target Parameter to link to. You can use the searchbar to find the Parameter you want.

```yaml
#Note:
User are able to select only one Target Parameter.
```

All done, now click OK to finish creating the Parameter Link.

![Target Parameter](../../assets\images\ParameterLink\PL-Target.gif)  
<sub>Note: the version on the image may not reflect the [latest version](https://diroots.com/revit-plugins/distem-bundle-for-autodesk-revit/).</sub>

---

## Delete Link

Select the links you have created and click the Delete Link button, or right-click and select the Delete Link option.

![Delete Link](../../assets\images\ParameterLink\PL-Delete.gif)  
<sub>Note: the version on the image may not reflect the [latest version](https://diroots.com/revit-plugins/distem-bundle-for-autodesk-revit/).</sub>

## Duplicate Link

Select the links you have created and click the Duplicate Link button, or right-click and select the Duplicate Link option.
Once the Link has been duplicated, click on the Edit button in the last column of the Link to edit the Link settings if you wish.

![Duplicate Link](../../assets\images\ParameterLink\PL-Duplicate.gif)  
<sub>Note: the version on the image may not reflect the [latest version](https://diroots.com/revit-plugins/distem-bundle-for-autodesk-revit/).</sub>

## Edit Link

On the Edit button in the last column of the Link to open the Link settings and change them if necessary.

![Edit Link](../../assets\images\ParameterLink\PL-EditLink.gif)  
<sub>Note: the version on the image may not reflect the [latest version](https://diroots.com/revit-plugins/distem-bundle-for-autodesk-revit/).</sub>

---

## Apply Link

Remember to define which elements you want to map before applying it. It can be applied to the Whole Model, only to elements in the Active View or only to Current Seclected elements. Use the radio button to select the desired option.
The next step is to select the checkboxes to choose the links to apply the mapping.

![Apply Link](../../assets\images\ParameterLink\PL-Apply.gif)  
<sub>Note: the version on the image may not reflect the [latest version](https://diroots.com/revit-plugins/distem-bundle-for-autodesk-revit/).</sub>

---

## Profiles

Be aware that when you close the plugin, you may lose the links you have created. To avoid this, save the profiles with the current links.

### Create Profiles

The profiles feature make it easy to save your settings and reuse them later. It is also a handy way for BIM Managers to create standard rules and share them across the organization.

Steps:

![DiStem Parameter profiles](../../assets\images\ParameterLink\PL-SaveProfile.gif)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

1. Click on the top-right dropdown to open the profiles list.
2. Click on the text input and name the profile (give it a meaningful name because this is the name that will show up in the profiles list)
3. Click on the save button to save profile.

### Import Profiles

The profiles feature make it easy to import existing profiles (e.g., profiles from a shared location).

Steps:

![DiStem Parameter Link Importing profiles](../../assets\images\ParameterLink\PL-ImportProfile.gif)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

1. Click on the top-right dropdown to open the profiles list.
2. Click on the 'Import' button.
3. Choose if you want to override the current list of profiles or if you want to append the profiles to your current list. 
4. Select the profiles file to be imported.

### Export Profiles

The profiles feature make it easy to export your current list of profiles.

Steps:

![DiStem Parameter Link profiles](../../assets\images\ParameterLink\PL-ExportProfile.gif)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

1. Click on the top-right dropdown to open the profiles list.
2. Click on the 'Export' button.
3. Select the folder location and filename. 

### Delete Profiles

Steps:

![DiStem Parameter Link Deleting profiles](../../assets\images\ParameterLink\PL-DeleteProfile.gif)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

1. Click on the top-right dropdown to open the profiles list.
2. Click on the dustbin icon next to the profile you want to delete from the list.
3. Click 'Yes' to confirm and delete the profile.

---