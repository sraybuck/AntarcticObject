# Antarctic Objects

**An Exploration of &#60;object&#60; Using Antarctic Artifacts**

This repository contains the files for a project on the newly added <object> element and its use when describing the physical appearance of objects. The goal of this project was to evaluate the current implementation of <object> and more specifically its child elements relating to physical description. We concluded that it may be helpful to include a way to subdivide or section off parts of objects since so much of our prose description ended up referencing different abstract or concrete parts of the object. Below is a list of all our files and their purposes:

* Objects.xml - our initial description of our six objects using the current implementation of <object>
* SectorCustomizations.odd - ODD file that has our customization that includes the new <objectSector> element which is used to define sectors and the new <sectorDesc> element which is used to describe sectors.
* ObjectSectorTest.xml - three examples of how to use <objectSector>
* SectorDescTest.xml - three examples of how to use <sectorDesc>
* out - contains .rnc and .rng of SectorCustomizations.odd
