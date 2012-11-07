# Welcome to SketchUp-to-DXF-STL

It's a SketchUp Ruby plugin that adds STL (STereoLithography) and AutoCAD DXF file export formats

## Installing the plugin

The latest version is available from http://www.guitar-list.com/download-software/convert-sketchup-skp-files-dxf-or-stl

To install the plugin you need to download the file "skp_to_dxf.rb" to your Sketchup plugins folder. This installation method will work with Sketchup 6, 7 and 8.

###Location of the Sketchup plugins folder,  [VERSION] stands for the version number of Sketchup (6, 7 or 8).

On a Windows PC. If you have installed Sketchup on the C: drive then this folder will be at C:\program files\google\google sketchup [VERSION]\plugins. 
On Mac OSX. The sketchup plugins folder is /Library/Application Support/Google SketchUp [VERSION]/SketchUp/Plugins

##Using the plugin
After copying this file, start Sketchup and you should now have an extra menu options (Export to DXF or STL) in the Sketchup Tools and File-export menu.

There are five export options:

    STL  triangles. Use this for Makerbot or Reprap style 3D printers
    DXF polyface mesh. This will give the most faithful reproduction of your original Sketchup model.
    DXF polylines: exports the outlines of each face as a polyline, sometimes useful for CAM toolpaths.
    DXF triangular mesh: breaks all the faces up into triangles
    DXF lines. This option exports the edges in your model as lines.

## License

License: Apache License, Version 2.0

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

