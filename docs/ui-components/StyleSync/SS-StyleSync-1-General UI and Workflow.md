---
layout: default
title: General UI and Workflow
parent: Style Sync User Guide
nav_order: 1
---


# Documentation: Style Sync Feature in DiStem

## Introduction

The Style Sync feature in DiStem allows users to convert all instances of a specific style into another. This applies to line styles, fill patterns, dimension styles, text styles, materials, and families.

The primary goal is to clean up undesired styles quickly without manually going into various Revit UIs while retaining the elements. These elements are remapped to the selected style, enabling the deletion of the non standard styles/families/patterns/materials.


![DiStem Style Sync - General - Style Sync](../../../assets\images\StyleSync\DS_SS_OpeningStyleSync.gif)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>



## Example Use Cases


![DiStem Style Sync - General - Cleanup](../../../assets\images\StyleSync\DS_SS_GenCleanup.gif)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

**Copy-Pasting Detail Elements:** Cleaning up unwanted line styles/line patterns may be introduced in a shared central model.

**Cleaning Materials inside Families:** Swiftly switching materials from imported families with user required materials.

**Cleaning CAD line styles:** Cleaning up line styles and materials after importing a CAD file.

**Standardizing Styles:** Reducing the number of duplicated text or dimension styles made by different users in a central model

**Cleaning up families:** Quickly replace multiple families using a easy to search and find UI


## Description

Each tab within the Style Sync feature contains a DataGrid displaying the styles (or patterns, materials, or families) in the project, along with the number of instances and a ComboBox for selecting the target style. Some tabs include additional columns and specialized filters.

After selecting the target styles and checking the ones to sync, users press the Sync button to update the styles of all elements. Users can then delete empty styles or use the Delete All button.


![DiStem Style Sync - General - Tabs and Sync](../../../assets\images\StyleSync\DS_SS_GenTabsAndSync.gif)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>


## Style Inspector

The Style Inspector window allows users to inspect styles in each element in finer detail, displaying each instance with its corresponding view (for detail elements) and providing a context menu to show selected instances in Revit. User can find and select

![DiStem Style Sync - Inspector](../../../assets\images\StyleSync\DS_SS_General_Inspect.gif)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>
