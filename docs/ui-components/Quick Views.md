---
layout: default
title: Quick Views
parent: User Guide
nav_order: 8
---

![DiStem Quick Views - Create internal views by Callouts, Elevations and Sections](../../)  


# Quick Views
{: .no_toc }
The Quick Views allows you to create multiple Callouts, Elevantions and Sections views from internal rooms and spaces.

## Core Features
{: .no_toc }
- Create Callouts from rooms and spaces
- Create Elevations and Sections from rooms and spaces
- Update views in batch
- Assign Shared Parameters into the views.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---
## Whole Model or Active View

Select the radio button to manage rooms and spaces from Whole Model or the Active View.
Note that, the table you show all rooms and spaces from current selected option. In this table you can see the level, number, name, and type from rooms and spaces, and the Status column will show if there are views created.

![DiStem Quick Views - Whole Model or Active View](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

### Select Types

In the first list, select if you want to create views from Rooms, Spaces or both.

![DiStem Quick Views - choose rooms/spaces](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

### Linked Files

Use the checkbox to choose the option to manage the rooms and spaces from linked files.

![DiStem Quick Views - linked files](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

### Status list

Open the Status List, and filter the rooms and spaces as Created, Not Created and Changed views.

![DiStem Quick Views - Filter by status](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

## Callout View

Lets create some Callouts Views. To make this, click on Callout Settings button.

### View tab

In this tab, you can manage all details to create the Callout views.

1. Choose the Callout Type

2. Select a scale to apply to the views.

3. Define the level of detail to create the views.

4. Choose the Phase from view.

5. If you want, select a View Template to create it.

6. Define a value to Offset from Callout boudary.

7. Choose if you want the Callout boudary as a rectangle or aligned with room/space boundary.

```yaml
#Note:
Use the Info icon to see the boudaries example.
```

![DiStem Quick Views - View tab](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

### Naming Configuration tab

Lets custom the view names.

On the first table see all the existing parameters you can use to naming the views. Select the parameters you want, and click on the arrow button to assign to the Selected Parameters table. You can also order the Selected Parameters using the arrows bellow the table.

```yaml
#Note:
Use the checkbox to also see the Project Information parameters.
```

```yaml
#Note:
Select the checkbox to add a default Field Separator between the selected parameters.
```

![DiStem Quick Views - select parameters to naming](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

1. Enter Custom Fields to naming the views.

2. Enter Custom Separators betwen the parameters to naming.

![DiStem Quick Views - custom field and custom separator](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

### Parameters tab

To manage this tab you need at least one Shared Parameter from Views category criated. Then, click on Add button to add a Shared Parameter to the views you will create.
Once you have added, open the list to select the parameter and on the second column assign a text value from it.

![DiStem Quick Views - Parameters tab](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

### Save settigs

Click on Apply to save the settings, and select the rooms and spaces you want to create the Callout views.
To finish, click on Create button, and wait for a few seconds to create the views.

```yaml
#Note:
You also can use the Select Rooms/Spaces buttons to choose them manually.
```

![DiStem Quick Views - create views](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

## Elevation and Section views

Lets create some Elevations and Setions Views. To make this, select in the list if you want to create Elevation or Section views, and click on Settings button.

### View tab

In this tab, you can manage all details to create the views.

1. Choose the Elevation/Section Type.

2. Select a scale to apply to the views.

3. Define the level of detail to create the views.

4. Choose the Phase from view.

5. If you want, select a View Template to create it.

6. Select the checkbox to Join Elevation Views into Single Marker. If the room is square or retangle, this option you put all views in as single marker.

![DiStem Quick Views - View tab](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

Now lets define the section height and offsets from rooms and spaces.

1. Section Height- open the list and choose if you want to apply the value From Instance or Absoulte, and then define de value to apply it.

2. Define the Offset Bottom value.

3. Enter an Offset Left value.

4. Enter an Offset Right value.

5. Define the distance before boundary.

6. Define the distance after boundary.

7. To conclude, define a Boundary break tolerance. For example, if there are small walls in the room, you can assign a tolerance value to create the views. Whether you want to create a view for each small wall, or a general view, without taking these smaller values into account.

```yaml
#Note:
Use the Info icon to see the boudaries and Offsets examples.
```

![DiStem Quick Views - View tab](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

### Naming Configuration tab

Lets custom the view names.

On the first table see all the existing parameters you can use to naming the views. Select the parameters you want, and click on the arrow button to assign to the Selected Parameters table. You can also order the Selected Parameters using the arrows bellow the table.

```yaml
#Note:
Use the checkbox to also see the Project Information parameters.
```

```yaml
#Note:
Select the checkbox to add a default Field Separator between the selected parameters.
```

![DiStem Quick Views - select parameters to naming](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

1. Enter Custom Fields to naming the views.

2. Enter Custom Separators betwen the parameters to naming.

![DiStem Quick Views - custom field and custom separator](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

Lets create a condition to count the views.

1. Define the follow order by Clockwise or Anticlockwise.

2. Choose the direction to stard.

3. Definde the style by number or alphabet.

4. Enter the value to start.

```yaml
#Caution:
To use the View Count condition, you must to select the View Count Parameter, in the previous table.
```

![DiStem Quick Views - custom field and custom separator](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

### Parameters tab

To manage this tab you need at least one Shared Parameter from Views category criated. Then, click on Add button to add a Shared Parameter to the views you will create.
Once you have added, open the list to select the parameter and on the second column assign a text value from it.

![DiStem Quick Views - Parameters tab](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

### Save settigs

Click on Apply to save the settings, and select the rooms and spaces you want to create the Elevations/Sections views.
To finish, click on Create button, and wait for a few seconds to create the views.

```yaml
#Note:
You also can use the Select Rooms/Spaces buttons to choose them manually.
```

![DiStem Quick Views - create views](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

## Right-click actions

Right-click on the room/space inside the table and you can:

- Delete Callout and Elevations/Sections.

- Open Callout and Elevations/Sections.

---

## Update Views

Update the Views of the selected Rooms/Spaces. All views from the selected Rooms are going to be deleted and new views are going to be created.

```yaml
#Note:
Details and dimensions will be lost.
```

![DiStem Quick Views - create views](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>