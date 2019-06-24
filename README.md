# DASSL Duck
There is a concept in software development known as "Rubber Duck Debugging" which is the act of vocalizing one's programming dilemma to an inanimate object, such as a rubber duck, and in doing so realize the cause of their problem. Here in DASSL we wanted to have our own branded duck for use by students at WCSU both past and present to help them solve their own coding dilemmas and also be reminded of the DASSL program. From this desire the DASSL Duck was born!  

The DASSL Duck is not actually rubber, but rather a 3D printed plastic model with the letters "DASSL" recessed and painted on the chest area. The duck model is a modified version of the 3D file titled ["Rubber Duck"](https://www.thingiverse.com/thing:139894) taken from [Thingiverse](https://thingiverse.com), designed by user [willie](https://www.thingiverse.com/willie/about) and licensed under [Creative Commons - Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/) which allows the public to copy, modify, distribute, and perform the work for any purpose without asking permission beforehand. This model follows the DASSL protocol of trying to build and use open-source software that benefits the public at no cost to them and was selected for this reason as the base of the current DASSL Duck.

## Design
The current iteration of the DASSL Duck was designed using the online 3D modeling software [Tinkercad](https://tinkercad.com), a simple online model editor that allowed for fast modification and iteration of the model. The 3D model was then exported as a .obj file and sliced by [Ultimaker Cura Software](https://ultimaker.com/en/products/ultimaker-cura-software), a free and open-source 3D model slicing program. The resulting .gcode file was then printed using a [Monoprice Maker Select 3D Printer v2](https://www.monoprice.com/product?p_id=13860&gclid=Cj0KCQjw6cHoBRDdARIsADiTTzaTkReRz-KWjMdBoxAuGKZEHuVaYLvsS76ZyLjN_BzlsVjv7bqrmqUaAl9KEALw_wcB) with [HATCHBOX Yellow PLA](https://www.amazon.com/HATCHBOX-3D-Filament-Dimensional-Accuracy/dp/B00J0GRREW/ref=sr_1_3?keywords=yellow+pla&qid=1561389931&s=gateway&sr=8-3) and painted using [Uni-posca Paint Marker Pens](https://www.amazon.com/Uni-posca-Paint-Marker-Pen-PC-1M8C/dp/B001MT893I/ref=sr_1_68?crid=2O3WLMSM8RX17&keywords=posca+paint+markers&qid=1561388944&s=gateway&sprefix=ppsca+paint+markers%2Caps%2C149&sr=8-68).

## Printer Settings
The settings that achieved the results in images/ are as follows: 
```
Layer Height: 0.1 mm
Infill Density: 15%
Printing Temperature: 215 degrees C
Build Plate Temperature: 60 degrees C
Print Speed: 50 mm/s
Retraction: yes
Generate Support: yes
Support Overhang Angle: 60 mm/s
Build Plate Adhesion Type: Skirt
```
Support was used for the models in the pictures, however others have printed without support with no issues. 

## Repository Content
This repository contains the current version of the DASSL Duck in a .obj 3D file format which should be compatible for any slicing engine. For convenience there is also the gcode/ directory that contains pre-compiled gcode for use on most standard FDM printers. There are multiple different sizes of the model with `DASSLduck.obj` being the standard size. The repository also contains an images/ directory that contains pictures of the current version (v5) in the top-level, as well as previous versions images in dedicated folders. There is no `v4` folder as there is almost no visual difference between `v4` and `v5` DASSL Ducks.