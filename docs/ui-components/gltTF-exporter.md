---
layout: default
title: glTF Exporter
parent: User Guide
nav_order: 5
---

![DiStem glTF Exporter - From Autodesk Revit to glTF.](../../assets/images/glTFExporter/glTF-Exporter-logo_x150.png)  


# glTF Exporter
{: .no_toc }
The glTF Exporter is an Autodesk Revit plugin that allows you to export your Autodesk Revit models to glTF file format.

## Core Features
{: .no_toc }
- quickly export the 'Active View' or the 'Current Selection'
- export by category
- export specific Revit families

## Advanced Features
{: .no_toc }
- Group geometry by 'Elements' or 'Materials'
- Compress the glTF files using 'Draco Compression' or 'Standard Compression'
- Export to glTF or GLB
- Export 2D Elements
- Export Normals with different precision levels (low, medium, high)
- Set up a default export location

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Export to glTF

Steps:
1. Open the glTF Exporter.
2. Choose if you either want to export the 'Active View' or the 'Current Selection'
3. Optional: Filter the elements using 'Rule-based Filters'.
4. Use the tree view to select the elements you want to export. 
5. Optional: tweak the default configuration.
6. Click on the 'Export' button.

![DiStem glTF Exporter - step by step](../../assets/images/glTFExporter/glTF-Exporter-Usage-Steps.png)  
<sub>Note: the version on the image may not reflect the [latest version](https://diroots.com/revit-plugins/distem-bundle-for-autodesk-revit/).</sub>

## Advanced Configuration

Steps:
1. Click on the 'Configuration' button.
2. Select if you want to group the meshes by elements or by materials.
3. Select the compression ('No Compression', 'Draco Compression', or 'Standard Compression').
4. Select if you want to export to glTF (JSON/ASCII) or GLB (Binary file format). Please note that both .gltf and .glb files may reference external binary and texture resources.
5. Select the export settings ('Export 2D Elements', 'Export Normals', 'Precision Level', and default export location).

![DiStem glTF Exporter - Advanced Configuration](../../assets/images/glTFExporter/glTF-Exporter-Advanced-Configuration.png)  
<sub>Note: the version on the image may not reflect the [latest version](https://diroots.com/revit-plugins/distem-bundle-for-autodesk-revit/).</sub>

## Viewing the 3D Model in the default Windows 3D Viewer 

Because glTF is a standard file format for three-dimensional data, it is compatible with with many platforms and technologies, such as ThreeJS, Unity, Unreal Engine, Microsoft 3D Viewer, etc..

![Microsoft 3D Viewer](../../assets/images/glTFExporter/Microsoft-3D-Viewer.png)