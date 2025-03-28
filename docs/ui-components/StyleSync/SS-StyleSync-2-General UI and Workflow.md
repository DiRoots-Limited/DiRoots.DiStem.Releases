---
layout: default
title: General UI and Workflow
parent: Style Sync User Guide
nav_order: 2
---

# Style Sync General Navigation Documentation

##  Overview

The Style Sync feature provides a user-friendly interface for managing and updating various styles within your project. This documentation outlines the general navigation and functionalities available.

###  Selection

The selection in the DataGrid allows for actions to be applied to multiple rows. 

- **MultiSelection:** Click and drag to select multiple rows
- **Ctrl Key:** Add or Remove rows one by one.
- **Shift Key:** Add all rows between the last selection and the next selection.
- **Select All**: Press **Ctrl + A** to select all rows in the window.
- **Checkboxes:** Use the checkboxes on the left to check the items you wish to Sync or Delete. Use the checkbox in the column header to check or uncheck all items.

![DiStem Style Sync - General - Selection](../../../assets\images\StyleSync\DS_SS_General_Selection.GIF)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

###  Context Menus

#### When right clicking on rows you have the main context menu:

![DiStem Style Sync - ContextMenu - Main](../../../assets\images\StyleSync\SS-ContextMenu-Main.png)

- **Inspect** - Show the inspector window with the selected styles.  
- **Show Elements** - Shows all elements that use the selected styles.  
- **Select Elements** - Selects all elements that use the selected styles.  
- **Delete** - Deletes the selected styles that are not in use.  
- **Expand All** - Expands all groups (visible only when grouping is applied).  
- **Collapse All** - Collapses all groups (visible only when grouping is applied). 


#### When right clicking on column headers you have the following context-menu:

![DiStem Style Sync - ContextMenu - Headers](../../../assets\images\StyleSync\SS-ContextMenu-Headers.png)

- **Clear Sorting** - Clears the sorting on this column.
- **Clear Filtering** - Clear the filtering on this column.
- **Hide Column** - Hides this column.
- **Show All Columns** - Shows all hidden columns that are available in the column settings.
- **Column Settings** - Opens the Column Settings window.
- **Stretch to Fill** - Resizes this column to evenly fill available space. Columns marked for stretching grow and shrink with window resizing.  
- **Auto Fit** - Resizes this column to match content and header size.  
- **Group by this Column** - Groups rows by this column. Supports multi-level grouping by using the order of selecting this option. 
- **Clear Groups** - Removes all grouping applied to the grid. 

###  Sorting

Column Headers: 
- **Click** - Sorts in ascending or descending order, according to the values of this column 
- **Ctrl + Click** - Adds a secondary sort on the data, according to the values of this column.

![DiStem Style Sync - General - Sorting](../../../assets\images\StyleSync\DS_SS_General_Sorting.gif)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>


###  Filtering

**Filter Symbol**: Notice the filter symbol on each header, it indicates if there's any filter active. Click on it to open the filtering menu:
-  **Clear Filter** - Clears the active filter on this column.
- **Text/Number filter** - Create specific rule based filters such as Contains, Begins with, Larger than, etc.
- **Search** - Filters the below checklist to values that match the input.
- **Check List** - Allows manually filtering specific values, by checking/unchecking from a list of available values.


![DiStem Style Sync - General - Filtering](../../../assets\images\StyleSync\DS_SS_General_Filtering.gif)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>


###  Column Settings
You can customize the columns displayed by accessing the column settings. Use this window to easily show and hide columns, group/ungroup them and, if possible, open the **Add Parameters** window.

![DiStem Style Sync - General Column Settings](../../../assets\images\StyleSync\DS_SS_General_ColumnSettings.GIF)
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

###  Add Parameters
This window that is only available in the Dimension Styles or Families tab. It allows you to choose between all available parameters and add them as columns on the datagrid.

![DiStem Style Sync - General Add Parameters](../../../assets\images\StyleSync\DS_SS_General_AddParameters.gif)
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

###  Column Grouping
You can group the data shown as groups by using group by this column option by right clicking the column headers. Allowing you to focus on what changes are necessary.

![DiStem Style Sync - General Column Grouping](../../../assets\images\StyleSync\DS_SS_General_ColumnGrouping.gif)
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>


###  Overall Search Bar
Quickly find data across all tabs using the overall search bar. Search bar remembers the last input even when you change tabs.

![DiStem Style Sync - Search Bar](../../../assets\images\StyleSync\DS_SS_General_SearchBar.gif)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

###  Bulk Actions
The Style Sync feature supports bulk actions, enabling you to select and synchronize multiple styles at once, further enhancing efficiency.

![DiStem Style Sync - Selection Modifiers](../../../assets\images\StyleSync\DS_SS_General_BulkActions.gif)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

###  Cleanup
After synchronizing styles, you can clean up duplicated and non-standard styles, making the project look cleaner and saving precious file size. This is especially useful in large projects under a shared work environment.
![DiStem Style Sync - Delete Options](../../../assets\images\StyleSync\DS_SS_General_DeleteOptions.gif)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

###  Error Handling
If there are any issues during the synchronization process, an error message will be displayed, providing details on the problem.

![DiStem Style Sync - Error Handling](../../../assets\images\StyleSync\DS_SS_General_ErrorHandling.gif)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

By following these guidelines, you can efficiently manage and update styles within your project, ensuring consistency and accuracy. If you have any further questions or need additional assistance, feel free to contact support@diroots.com