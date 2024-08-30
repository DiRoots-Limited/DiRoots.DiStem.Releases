---
layout: default
title: Family Thumbnail Generator
parent: User Guide
nav_order: 8
---

![DiStem Family Thumbnail Generator - Effortlessly create thumbnails/preview images of multiple RFA files in a snap](../../assets\images\Family-thumbnail\thumbnail-logo.png)  


# Family Thumbnail Generator
{: .no_toc }
The Family Thumbnail Generator allows you to create thumbnails/preview images of multiple RFA files in a snap. You can also choose the perspectives, display style, and detail level to create the most eye-cathing previews. Plus, hide elements that clutter your visual representation for a crisp, clean look.

## Core Features
{: .no_toc }
- Create thumbnails/preview images of the current family or several families in batches.
- Customize the appearance by default or for each category.
- Customize the general settings for creating the thumbnails/preview images.
- Update the current family.
- Update several families in batch.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Settings

Firstly, it's important to define the default settings for creating Family Thumbnail Generators.

### Appearance Settings

#### Default Appearance
These settings will be applied to all families. Set the Display Style and Detail Level for 3D and 2D families, and the View Type for 3D families.

![Family Thumbnail Generator - default appearance](../../assets\images\Family-thumbnail\FT-Da-Default.gif)  
<sub>Note: the version on the image may not reflect the [latest version](https://diroots.com/revit-plugins/distem-bundle-for-autodesk-revit/).</sub>

#### Override Appearance By Category

This section allows you to create conditions by categories, to override the default appearance settings.

1. Click on Add new condition.

2. Click on the first box to select the categories. the categories available in the first table are displayed and you can move the categories you want to the Selected Categories table.

3. Choose the View type from the drop-down list.

4. Select the Display Style from the drop-down list.

5. The last step is to select the Detail level.

![Family Thumbnail Generator - override appearance](../../assets\images\Family-thumbnail\FT-As-Override.gif)  
<sub>Note: the version on the image may not reflect the [latest version](https://diroots.com/revit-plugins/distem-bundle-for-autodesk-revit/).</sub>

### General Settings

1. Enter a name for the Thumbnail View.

2. The next step is to check whether you want to export images, and whether you want to resize image to fit or keep 1:1 aspect ratio.

3. The last step is to select the settings you want to export.

Click the Save button to apply the settings.

![Family Thumbnail Generator - general settings](../../assets\images\Family-thumbnail\FT-Gs-General.gif)  
<sub>Note: the version on the image may not reflect the [latest version](https://diroots.com/revit-plugins/distem-bundle-for-autodesk-revit/).</sub>

---

## Update Current

Open a family in the Family Editor mode, then open the DiStem tab and click to Update Current.

![Family Thumbnail Generator - update current family](../../assets\images\Family-thumbnail\FT-Uc-Current.gif)  
<sub>Note: the version on the image may not reflect the [latest version](https://diroots.com/revit-plugins/distem-bundle-for-autodesk-revit/).</sub>

---

## Update Batch

Click to update families in batches.

1. Source Families
First, select whether you want to Load from folder or Update opened families.

2. If you choose to Load from folder, select the location of the source folder.

3. Select the Output Location.

```yaml
#Note:
Select the checkbox to Save updated families in the same source location (backups will be kept).
When you select this option, you do not need to enter a location path.
```
Click on the Update button to start exporting the families.

![Family Thumbnail Generator - update in batch](../../assets\images\Family-thumbnail\FT-Uc-Batch.gif)  
<sub>Note: the version on the image may not reflect the [latest version](https://diroots.com/revit-plugins/distem-bundle-for-autodesk-revit/).</sub>