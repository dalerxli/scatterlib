# Near field intensity #

Wikipedia article [near field](http://en.wikipedia.org/wiki/Near_and_far_field) describes near and far field concepts (mostly in applications to an antenna). Similar concept applies to light scattering by particles.

There are several codes which can calculate near field intensity.

## Barber and Hill near field codes for spheres, cylinders, and axisymmetric particles ##
These codes were published in "Light Scattering by Particles: Computational Methods", P.W. Barber and S.C. Hill, 1990 by World Scientific Publishing. There are several programs
which may be used to calculate the near field intensity. They can be used for homogeneous sphere, infinite cylinder, and axisymmetric non-spherical particles.

The source code is available here [barber.zip](http://scatterlib.googlecode.com/files/barber.zip).

| Name|Description|
|:----|:----------|
|T8.for | internal intensity distribution for  axisymmetric particles (T-matrix) - 2D and 3D - use A matrix|
|T9.for  | external intensity distribution for axisymmetric particles - 2D and 3D - use T matrix|
|C6.for | Mie solution internal intensity distribution for a cylinder (normal incidence)- 2D and 3D|
|C7.for | Mie solution external intensity distribution for a cylinder (normal incidence)- 2D and 3D|
|S7.for | Mie solution for a sphere internal intensity distribution - 2D and 3D|
|S8.for | Mie solution for a external intensity distribution - 2D and 3D|

## Near field for cluster of spheres ##

| Name|Description|
|:----|:----------|
|[GMM-field](http://scatterlib.googlecode.com/files/GMM_FIELD.zip) |Moritz Ringler extension of  Xu's GMM program  published in "Plasmonische Nahfeldresonatoren aus zwei biokonjugierten Goldnanopartikeln", Dissertation Ludwig Maximilians Universität, München 2008 |

Other references

Ringler, M.; Schwemer, A.; Wunderlich, M.; Nichtl, A.; Kurzinger, K.; Klar, T. A.; Feldmann, J. Phys. Rev. Lett. 2008, 100,
203002.


## Coated sphere ##
| Name|Description|
|:----|:----------|
|BHFIELD code|Honoh Suzuki and I-Yin Sandy Lee, Calculation of the Mie scattering field inside and outside a coated spherical particle, International Journal of Physical Sciences Vol. 3 (1), pp. 038–041, January 2008. Available from Honoh Suzuki honoh@sci.u-toyama.ac.jp |

## Near field for general non-spherical particles ##
Near field can be calculated in discrete dipole approximation. Wikipedia article [codes for discrete dipole approximation](http://en.wikipedia.org/wiki/Discrete_dipole_approximation_codes) provides documentation of various codes and relevant links. Wikipedia article on [discrete dipole approximation](http://en.wikipedia.org/wiki/Discrete_dipole_approximation) provides details of the method, applications, and references.


|Source code|Description|
|:----------|:----------|
|[DDSCAT and DDFIELD](http://code.google.com/p/ddscat/) | Google code distribution of DDSCAT by Bruce Draine and Piotr J. Flatau|
|[a-dda](http://code.google.com/p/a-dda/) | Google code distribution of a-dda code by A. G. Hoekstra and M. A. Yurkin|

Other references:

DDFIELD is described in Draine B. T. and P. J. Flatau, “Discrete-dipole approximation for periodic targets: theory and tests,” (2008) J.
Opt. Soc. Am. A 25, 2693–2703.

Hoekstra, A. J. Rahola, and P. Sloot, “ Accuracy of internal fields in volume integral equation simulations of light
scattering,” (1998), Applied Optics 37, 8482–8497.


## Other methods ##
|Name|Description|Reference|
|:---|:----------|:--------|
|NFM-DS|Null Field Method with Discrete Sources (T-Matrix)|A. Doicu and T. Wriedt, Near-field computation using the null-field method, J. Quant. Spectrosc. Radiat. Transf. 111, 466–473, 2010|
|FEM  | COMSOL Multiphysics | COMSOL Multiphysics demonstration CD-ROM can be requested at http://www.comsol.com|
|MMP 3D | MMP method |C. Hafner and L. Bomholt, The 3D electromagnetic wave simulator, Wiley, 1993|

Reference:

Karamehmedovic M., R. Schuh, V. Schmidt, T. Wriedt, C. Matyssek, W. Hergert, A. Stalmashonak, G. Seifert and O. Stranik, “Comparison of numerical meutation for metallic nanoparticles,” (2011), Optics Express 19, 8939.