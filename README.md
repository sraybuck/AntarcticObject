# Antarctic Objects

**An Exploration of &#60;object&#62; Using Antarctic Artifacts**

This repository contains the files for a project on the newly added &#60;object&#62; element and its use when describing the physical appearance of objects. The goal of this project was to evaluate the current implementation of &#60;object&#62; and more specifically its child elements relating to physical description. We concluded that it may be helpful to include a way to subdivide or section off parts of objects since so much of our prose description ended up referencing different abstract or concrete parts of the object. Below is a list of all our files and their purposes:

* Objects.xml - our initial description of our six objects using the current implementation of &#60;object&#62;
* SectorCustomizations.odd - ODD file that has our customization that includes the new &#60;objectSector&#62; element which is used to define sectors and the new &#60;sectorDesc&#62; element which is used to describe sectors.
* ObjectSectorTest.xml - three examples of how to use &#60;objectSector&#62;
* SectorDescTest.xml - three examples of how to use &#60;sectorDesc&#62;
* out - contains .rnc and .rng of SectorCustomizations.odd
