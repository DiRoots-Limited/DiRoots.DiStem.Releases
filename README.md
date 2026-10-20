DiStem bundle for Autodesk Revit contains several Revit add-ins to boost your productivity. This bundle will help you to manage your BIM model data (extract and map elements’ properties and parameters), clean up the Revit model, remove revision clouds, transfer, measure distances in 2D & 3D views, get elements coordinates, and export to glTF.

### Included in DiStem bundle
- Properties Extraction Mapping to quickly extract hidden parameters and properties (e.g., Location – X, Y, Z Coordinates) from the model elements and inject them into existing or new instance shared parameters.
- Model Cleanup to quickly batch delete Views, Schedules, Sheets, View Templates, Filters, Links, Imports, and Images from your Revit Models. Easily select the elements you want to remove and remove them all with a single click.
- Revision Clouds Remover plugin to batch remove revision clouds from your Autodesk Revit model.
- 2D & 3D Measure to measure in 2D and 3D views (between 2 points, the length of an edge, get coordinates from a single point).
- glTF Exporter to quickly export your Autodesk Revit models to glTF file format.
- CAD Manager plugin to show/hide and colorize CAD layers in the Revit model.
- Project Standards to transfer multiple elements (e.g., Views, Sheets, View Templates, Doors, Windows) from one project to multiple projects in one go.
- StyleSync to quickly clean up or merge undesired, unused, and duplicate styles. Supports line styles, line patterns, fill regions, fill patterns, dimensions, text styles, materials, and families.
- more tools are coming soon.

### Supported Revit Versions
2019, 2020, 2021, 2022, 2023, 2024, 2025, 2026, and 2027.

### Useful links
[User Guide](https://docs.distem.diroots.com/) 
[Provide Feedback](https://diroots.com/contact-us/)
[Custom Software Development](https://diroots.com/custom-software-development/)

[DiRoots Limited](https://diroots.com/) 

### Preview the documentation locally

The documentation source is on `gh-pages`; documentation pull requests should target that branch.

Install Ruby 3.1 with Ruby+Devkit on Windows, including the MSYS2 development toolchain, and Bundler 2.5.23. Keep the Ruby installation path free of spaces (for example, `C:\Ruby31-x64`), or use its Windows short path on `PATH` when running Bundler. The Gemfile pins the GitHub Pages dependency bundle; commit Gemfile.lock when intentionally updating dependencies.

From the documentation checkout, run:

```powershell
gem install bundler -v 2.5.23
bundle _2.5.23_ config set --local path vendor/bundle
bundle _2.5.23_ install
bundle _2.5.23_ exec jekyll serve --host 127.0.0.1 --port 4000 --baseurl=""
```

Open <http://127.0.0.1:4000/>. Stop the preview with Ctrl+C. For a build without the server, run `bundle _2.5.23_ exec jekyll build`.

The generated `_site` directory, dependency cache, and local preview files are ignored by Git. The local server does not publish changes to GitHub Pages.

Feature guide articles keep their existing URLs. Former “User Guide” landing URLs redirect to the articles, preserving query strings and heading fragments when JavaScript is enabled, with a direct link available otherwise.

Single-page guides list their sidebar sections in `nav_sections`, using a title and the existing heading anchor for each link. Keep these entries aligned with the guide's main table-of-contents sections.

Address:
R. da Marcha Gualtariana, 628
4810-264, Guimarães
