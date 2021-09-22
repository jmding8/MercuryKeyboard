# Case 3d Printing Tips

* For best results, use the included PrusaSlicerPresliced.3mf project file. It includes tweaks like manually placed seams and modifier-meshes which help improve surface quality.
* For low-profile builds, use your slicer to cut off the top 2mm of the part (leaving 6.8mm total height).
* As of late 2020, PrusaSlicer is recommended over Cura because the latter's thin-wall implementation is buggy.
* If you still want to slice yourself instead of using the recommended PrusaSlicerPresliced.3mf file, here are some suggested settings:
  * 0.5mm line width (can be printed with a 0.4mm nozzle with no issues)
  * 0.20mm layer heights
  * 2 perimeters
  * no supports
