# Scattering by spheres #
Mie theory, also called Lorenz-Mie theory or Lorenz-Mie-Debye theory, is an analytical solution of Maxwell's equations for the scattering of electromagnetic radiation by spherical particles (also called Mie scattering) in terms of infinite series. The Mie solution is named after its developer, German physicist Gustav Mie. However, Danish physicist Ludvig Lorenz and others independently developed the theory of electromagnetic plane wave scattering by a dielectric sphere. The term "Mie solution" is sometimes used more generically for any analytical solution in terms of infinite series, for example in case of concentric spheres, or cluster of spheres, or infinite cyliders. However, in this section we consider only homogeneous spheres.

Wikipedia article on  [Mie approximation](http://en.wikipedia.org/wiki/Mie_theory) provides description of the theory.
Wikipedia article [codes for electromagnetic scattering by spheres](http://en.wikipedia.org/wiki/Codes_for_electromagnetic_scattering_by_spheres) provides list of the codes and relevant links and references.

## Bohren and Huffman codes ##
This code was originally published in the Appendix of "Absorption and Scattering of Light by Small Particles"  by Bohren, Craig F., Huffman, Donald R, 1983, Wiley, New York, 530 pages.
| Name| Author | Type|Language|Description|
|:----|:-------|:----|:-------|:----------|
| [bhmie (Fortran)](http://scatterlib.googlecode.com/files/bhmie-f.zip) | Bohren and Huffman |  Mie| Fortran|This code is published in the appendix of Bohren and Huffman light scattering book and is probably one of the most heavily used Mie codes. Well documented and highly recommended.  The code is available here with slight extension; calculation of asymmetry paremeter (done by B. T.  Draine of Princeton University) |
| [bhmie (C)](http://scatterlib.googlecode.com/files/bhmie-c.zip) | Bohren and Huffman |  Mie| C| Translation of  Bohren and Huffman code|
| [bhmie (IDL)](http://scatterlib.googlecode.com/files/bhmie-idl.zip) | Bohren and Huffman |  Mie|  IDL| Translation by Piotr Flatau |
| [bhmie (Matlab)](http://scatterlib.googlecode.com/files/bhmie-matlab.zip) | Bohren and Huffman |  Mie| Matlab| Translation  |
| [bhmie (Python)](http://scatterlib.googlecode.com/files/bhmie_herbert_kaiser_july2012.py) | Bohren and Huffman | Mie | Python| Herbert Kaiser (University of Konstanz, Germany)|

## Bohren and Huffman Mie Graphical User Interfaces ##
|Name|Author|Type|Language|Description|
|:---|:-----|:---|:-------|:----------|
|Mieplot|Philip Laven|Mie|Visual Basic|Based on the BHMIE code, this Visual Basic interface offers an easy-to-use interface providing graphs of intensity v. scattering angle, wavelength, radius and refractive index. [Mieplot home page](http://www.philiplaven.com/mieplot.htm)|

## Other single sphere Mie codes ##
| Name| Author | Type| Language| Description|
|:----|:-------|:----|:--------|:-----------|
|[MIEV0](http://scatterlib.googlecode.com/files/wiscombe_miev.zip)|  Wiscombe | Mie | Fortran| This code comes with extensive set of self-tests and extensive documentation. |
|[CAM](http://scatterlib.googlecode.com/files/wiscombe_mieapx.zip) | Wiscombe | Approximation | Fortran| For large size parameters!  A package of routines to calculate the three Mie efficiency factors Q-ext, Q-abs and Q-pr (extinction, absorption, radiation pressure) using CAM approximations. These approximations are only useful (accurate to better than 10% or so) for size parameters above about 20 for Q-ext and above about 100 for Q-abs and Q-pr. Note that the Mie curves have a lot of ripple which makes comparisons at individual size parameters almost useless; you must plot the Mie and approximate curves for a short range of size parameter to see the overall accuracy of the approximations. |

## Barber and Hill scattering by a sphere codes (Mie solution) ##
These codes were published in "Light Scattering by Particles: Computational Methods", P.W. Barber and S.C. Hill, 1990 by World Scientific Publishing. There are eight computer programs which may be used to calculate the light scattered by a sphere. One auxiliary program calculates test results using the small-particle approximation.  A second auxiliary program determines array dimensions for the eight basic programs.

The source code is available here [barber.zip](http://scatterlib.googlecode.com/files/barber.zip).

| Name|Description|
|:----|:----------|
|S1.for|    (a)  efficiencies (ext.,sca.,abs.) vs size parameter, (b)  intensity at a scattering angle vs size parameter, (c)  angular scattering over a plane|
|S2.for |   angular scattering in all directions|
|S3.for |   scattering matrix calculations|
|S4.for |   internal and external coefficients vs size parameter|
|S5.for |   angle-averaged intensities, internal and near-field|
|S6.for |   surface intensity - internal and external|
|S7.for |   internal intensity distribution - 2D and 3D|
|S8.for |   external intensity distribution - 2D and 3D|
|ray.for |  calculate results using small-particle approximation|
|dim.for  | obtain array dimensions for all programs|


## Coated sphere ##
|Name|Author|Type|Description|
|:---|:-----|:---|:----------|
|[BHCOAT](http://scatterlib.googlecode.com/files/bhcoat.zip)|Bohren and Huffman|coated sphere|This code is published in the appendix of Bohren and Huffman light scattering book|
|[DMlLAY](http://scatterlib.googlecode.com/files/wiscombe_dmilay.zip)|Toon and Ackerman|coated sphere|This subroutine computes electromagnetic scattering by a stratified sphere (a particle with a spherical core surrounded by a spherical shell. Applied Optics, 20, 3657, 1981|

## Multiple spheres ##
|Name|Author|Type|Description|
|:---|:-----|:---|:----------|
|[GMM](http://scatterlib.googlecode.com/files/xu_codes.zip), [documentation](http://scatterlib.googlecode.com/files/xu_description.zip), [papers](http://scatterlib.googlecode.com/files/xu_papers.zip)|Xu|multisphere|Fortran codes which calculate (exactly) electromagnetic scattering by an aggregate of spheres in a single orientation or at an average over individual orientations (these codes were previously available on http://www.astro.ufl.edu/~xu/codes.htm)|
|[GMM near field](http://scatterlib.googlecode.com/files/GMM_FIELD.zip)|Xu and Moritz Ringler |multisphere nearfield|Fortran codes which calculate (exactly) electromagnetic scattering by an aggregate of spheres including nearfield extension by Moritz Ringler|
|[Mackowski](http://scatterlib.googlecode.com/files/mackowski_spheres.zip)|Mackowski|multiplesphere|codes for calculation of the scattering matrix and cross sections of neighboring, non-intersecting spheres.|