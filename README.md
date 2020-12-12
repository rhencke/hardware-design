# RE:Flex Dance Pad Hardware Designs
This repository contains source documents and manufacturing files for the RE:Flex Dance Pad's mechanical parts. It was created using [Fusion 360](https://www.autodesk.com/products/fusion-360/). However, future versions will be built with FreeCAD, due to Fusion's new pricing plan.

In this repository you will find:
- Fusion 360 source archives for the v1 (deprecated, and non-final) and v2 dance pads. These archives can be used to act as a reference model of RE:Flex Dance Pads, and future revisions.
- A folder of parts to be 3D printed in PLA.
- Parts lists for building a pad, bar, and doubles connectors. Currently this only lists the European vendor 'Motedis' parts for the base frame. It can be replicated with similar parts from 8020 and other vendors.

![](images/cad-model.png?raw=true "CAD Pad")

## Getting your own

Under part-lists.txt you can see a full list of parts required to complete this project. You can treat it as your own checklist. Please also save a list of where you have your parts, and feel free to submit it along with your country. 

Currently, you will also require a soldering iron for the through-hole electronics parts, and an M8 allen key to secure the entire framework.

## Future Improvements

The following changes could help in the future to provide for a better project:
- More investigation into different bar options would be nice. Currently the bars holding screws have to be tightened strongly to avoid it slipping, which is a bit of a hazard if someone leans their full weight on the bar and hasn't tightened the screws very well.
- The feet only support 150kg each, which may be a problem if someone were to go out of their way to break them. So other options could be useful here.
- Previous iterations of the panel to sensor adapters have been the weak point most likely to break. The current version seems good, but this is still worth looking at, considering it's fundamental to the pad functioning.
- Better cable routing. It's currently a bit ugly all around.
- Less manual positioning of parts. Currently, you have to 'eyeball it' a little bit as you place panels down onto their velcro holders. It's also a little bit of a manual task to ensure aluminium extrusion spacings and sensor holder positions. Sometimes this requires re-doing certain steps of the build as a result. I've included some 'spacers' that can be 3D printed for the latter tasks, but the former is still going to be a bit difficult.
- A method to connect pads for doubles while removing the outer pad extrusions to reduce distance between pads.
- A more dedicated placement for the I/O board (potentially extending the front of the pad) so that it can fit within a 9 panel pad.
- A configuration utility to provide parameterized 3D printed parts would be very useful here so that the end user doesn't have to deal with CAD software.
- We should have a 'sourcing' folder that lists parts and how they can be easily acquired in multiple different countries.
- We should also really have a nicely formatted build guide, as currently the user has to use the CAD model as their own reference.
- Switching the sources to FreeCAD would be a huge improvement.

## License

For license details, see LICENSE file