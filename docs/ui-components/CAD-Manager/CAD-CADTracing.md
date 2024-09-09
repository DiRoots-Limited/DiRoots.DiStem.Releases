---
layout: default
title: CAD Tracing
parent: CAD Manager User Guide
nav_order: 2
---

# CAD Tracing
{: .no_toc }
CAD Tracing allows you to convert the Layers or Element Types of the imported DWG into Revit elements, such as Legend or Drafting View.

## Core Features
{: .no_toc }
- Convert DWG elements in Revit Elements.
- Filter by Layers or Element Types.
- Create Legend or Drafting view.
- Export/Import CAD mapping.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

### CAD Link

This first drop-down list shows the list of DWGs imported into the project.

![DiStem CAD Tracing - choose imported DWG](../../../assets\images\CADManager\CT-CADLink.gif)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

### Sort list by

In the second drop-down list, choose whether you want to filter the elements in the DWG file by Layers or Element types.

![DiStem CAD Tracing - filter by layer or element type](../../../assets\images\CADManager\CT-SortList.gif)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

## Tracing

The table below lists all the layers in the selected DWG.
Expand the desired layer and, in the second column (tracing), use the drop-down list to choose the type of Revit element you want to convert.

![DiStem CAD Tracing - trancing layers](../../../assets\images\CADManager\CT-Tracing.gif)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

### Search Layers

Use the searchbox to search by specifc layers.

![DiStem CAD Tracing - Search layers](../../../assets\images\CADManager\CT-Search.gif)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

### Right-click

Use the shortcuts with the right mouse click.

- Expand all Layers
- Collapse all layers
- Hide Unchecked layers

![DiStem CAD Tracing - context menu](../../../assets\images\CADManager\CT-RightClick.gif)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

## Creating views

Finally, to complete the mapping, let's create a new view.

1. Choose the type of view you want to create, either Legend or Drafting View. Use the radio button to choose the type of view.

2. The next step is to choose whether you want to create a new view or overlay an existing one.

![DiStem CAD Tracing - new or existing view](../../../assets\images\CADManager\CT-View.gif)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

```yaml
# Note:
- If the user chooses to create a new view, they must enter a name for the view in the field below.
- If the user chooses to overlay an existing view, they must select the view they want to overlay.
```

### Create

Click on the “Create” button to execute the mapping and create the view as selected.

![DiStem CAD Tracing - create](../../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

## Export/Import CAD Mapping

Once you have configured the DWG layers/elements types to map in Revit, export a file that can be shared with your team or used in other projects.

![DiStem CAD Tracing - export CAD Mapping](../../../assets\images\CADManager\CT-ExportImport.gif)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>