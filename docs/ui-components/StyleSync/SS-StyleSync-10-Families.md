---
layout: default
title: Families
parent: Style Sync User Guide
nav_order: 10

---

# Families Documentation

##  Overview

The Families tab displays allows you to replace families with other similar families.

When replacing a family the types of the new family will be matched to the names of the existing family's types. If a matching type is not found a default will be chosen.

By default only duplicate families are shown, which in the context of this tab means families whose name is contained in another family's name.


##  Default Columns

The default columns include:

![DiStem Style Sync - Families UI](../../../assets\images\StyleSync\DS_SS_FM_UI.png)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>


**Family Category:** The category to which the family belongs.

**Name:** The name of the family.

**Instances:** The number of instances of the family in the project.

**Replace With:** Options for synchronizing the family with another.

### Additional Columns

You can include the following columns using the column settings to facilitate faster decision-making:**

**Placement Type:** The type of placement for the family (e.g., wall-based, floor-based).

**Type:** The specific type within the family.

**Type Counts:** The count of each type within the family.

##  Instructions

![DiStem Style Sync - Sync Families](../../../assets\images\StyleSync\DS_SS_FM_SyncFamilies.gif)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>


1. **Choose Replacement:** In the Replace With column, select the family that you want to replace the current one. It will be automatically checked.
1. **Sync:** Click the Sync button to change the Revit families instantly.

### Notes

- Only families of the same category are available in the Replace Width column.

- The duplicates will be the first ones on the list

- Please ensure that the selected families share the same placement type. This is crucial for avoiding errors during the synchronization process.

##  Additional Information

**Column Settings:** You can customize the columns displayed by accessing the column settings. This allows you to tailor the view to your specific needs and preferences.

**Filtering Options:** Use the filtering options on each column to narrow down the list of families based on that column data.

**Bulk Actions:** The Families tab supports bulk actions, enabling you to select and synchronize multiple families at once, further enhancing efficiency.

**Error Handling:** If there are any issues during the synchronization process, an error message will be displayed, providing details on the problem and steps to resolve it.

By following these guidelines, you can efficiently manage and update families within your project, ensuring consistency and accuracy. If you have any further questions or need additional assistance, feel free to contact support@diroots.com