# Scattering by cylinders #
Wikipedia article on  [Mie approximation](http://en.wikipedia.org/wiki/Mie_theory) provides description of the theory.
Wikipedia article [codes for electromagnetic scattering by cylinders](http://en.wikipedia.org/wiki/Codes_for_electromagnetic_scattering_by_cylinders) provides list of the codes and relevant links and references.


## Cylinder scattering codes ##
|Name | Author |Type |Description/References|
|:----|:-------|:----|:---------------------|
|[BHCYL](http://scatterlib.googlecode.com/files/bhcyl.zip)|Bohren and Huffman|cylinder|This code is published in the appendix of Bohren and Huffman light scattering book|
|[cylm](http://scatterlib.googlecode.com/files/mackowski_cylm.for)|Daniel Mackowski| cylinder, oblique incidence|Calculates efficiencies for slant incidence|
|[ASMAA](http://scatterlib.googlecode.com/files/SCAOBLIQ2_ver83.for)|Hashim A. Yousif|Scattering of EM light from cylinder at oblique incidence|H.  A.  Yousif  and  E.  Boutros,  "A  FORTRAN  code  for  the scattering of EM-plane waves  by an infinitely  long cylinder at oblique  incidence,"  Comput.  Phys.  Commun.  69,  406-414 (1992)|

## Barber and Hill codes for scattering by an cylinder at normal incidence ##

These codes were published in "Light Scattering by Particles: Computational Methods", P.W. Barber and S.C. Hill, 1990 by World Scientific Publishing. There are seven computer programs which may be used to calculate the light scattered by a cylinder when a plane wave is incident perpendicular to the cylinder axis.  One auxiliary program calculates test results using the small-particle approximation.  A second auxiliary program determines array dimensions for the seven basic programs.

The source code is available here [barber.zip](http://scatterlib.googlecode.com/files/barber.zip).

Notice that c6.for and c7.for calculate near field intensity.

|Name|Description|
|:---|:----------|
|C1.for  |  (a)  efficiencies (ext.,sca.,abs.) vs size parameter, (b)  intensity at a scattering angle vs size parameter, (c)  angular scattering over a plane|
|C2.for   | (b) and (c) in program C1.for except for a finite aperture rather than an infinitesimal aperture|
|C3.for |   internal and external coefficients vs size parameter|
|C4.for |   angle-averaged intensities, internal and near-field|
|C5.for |   surface intensity - internal and external|
|C6.for |   internal intensity distribution - 2D and 3D|
|C7.for |   external intensity distribution - 2D and 3D|
|ray.for  | calculate results using small-particle approximation|
|dim.for  | obtain array dimensions for all programs|
