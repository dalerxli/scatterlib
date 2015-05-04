# Anomalous diffraction approximation #

It is known under several names: van de Hulst approximation, eikonal approximation, high energy approximation, soft particle approximation

Anomalous diffraction approximation (ADT) offers very approximate but computationally fast technique to calculate extinction, scattering, and absorption efficiencies. Absolute value of refractive index has to be close to 1, and size parameter should be large. However, semi-empirical extensions to small size parameter, and larger refractive index are possible. The main advantage of the ADT is that one can (a) Calculate, in closed form, extinction, scattering, and absorption efficiencies for many typical size distributions; (b) Find solution to the inverse problem of predicting size distribution from light scattering experiments (several wavelengths); (c) For parameterization purposes of single scattering (inherent) optical properties in radiative transfer codes. Basic ADT for sphere is just several lines of code. It is amazing that these expressions can be analytically integrated for several size distributions.

Wikipedia article on [anomalous diffraction approximation](http://en.wikipedia.org/wiki/Anomalous_Diffraction_Theory) provides basic description of the theory.

The name eikonal approximation was originally used in optics but is now used almost exclusively in quantum mechanics. In ray optics one assumes that light travels
in a straight line and when the particle is soft (doesn't bend light) an "image" (eikon) is formed by light traveling through a particle in a straight line.


|Name | Author | Description |
|:----|:-------|:------------|
|[ADSCAT](http://scatterlib.googlecode.com/files/adscat.zip) | P. J. Flatau | ADT implementation |