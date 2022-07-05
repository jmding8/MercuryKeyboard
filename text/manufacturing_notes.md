# Manufacturing Notes



## PCBs
* [The PCB files are here](/pcb/v1.2).
* There are 5 total PCB files. They were designed with specific thicknesses for clearance reasons:
  * Logic PCB: 1.6mm
  * Left base: 1.2mm
  * Right base: 1.2mm
  * Left plate: 1.2mm
  * Right plate: 1.2mm
* It is strongly recommended to have the diodes pre-soldered by the PCB manufacturer.



## Optional 3D Printed Case

### Split builds
* [The case files are here](/case/split_case_with_prusa_slicer_settings.3mf).
* For wired builds, delete Body53_1 and Body54_1 to make room for the TRRS sub-boards to stick out through.
![TRRS cutouts in green](/images/case/trrs_cutout.png)
* The case is designed around PrusaSlicer. Cura (as of 2021) handles thin walls poorly, and also treats adjoining parts differently.
* Use PrusaSlicer and open the 3mf file as a project file (and not as a pure geometry / mesh).
* The project file includes slicer settings which implement many tweaks and optimizations that help maximize print quality.
* The top part was printed from the project file. The bottom part was sliced more conventionally.
![TRRS cutouts in green](/images/case/slicer_comparison.jpeg)

