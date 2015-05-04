# Approximations #
Several methods offer approximate but sometimes computationally fast techniques to light scattering by particles. Applicability of these approximate methods depends on refractive index, size parameter, phase shift of light within a particle. H. C. van de Hulst provides good characterization of these various methods.


Anomalous diffraction approximation (ADT, ADA, anomalous diffraction theory, van de Hulst approximation, eikonal approximation, high energy approximation, soft particle approximation) applies when an absolute value of refractive index is  close to 1, and size parameter should be large. The main advantage of the ADT is that one can (a) calculate, in closed form, extinction, scattering, and absorption efficiencies for many typical size distributions; (b) find solution to the inverse problem of predicting size distribution from light scattering experiments (several wavelengths); (c) for parameterization purposes of single scattering (inherent) optical properties in radiative transfer codes. Basic ADT for sphere is just several lines of code. Wikipedia article on [anomalous diffraction approximation](http://en.wikipedia.org/wiki/Anomalous_Diffraction_Theory) provides basic description of the theory.


|  Approximation | Refractive index m| Size parameter x| Phase shift x\*abs(m-1) |Wikipedia| Codes |
|:---------------|:------------------|:----------------|:------------------------|:--------|:------|
|Rayleigh scattering| abs(mx) very small | very small |  |[Rayleigh scattering](http://en.wikipedia.org/wiki/Rayleigh_scattering) |  |
|Geometric optics|  | very large| very large| [Geometrical optics](http://en.wikipedia.org/wiki/Geometrical_optics) |  |
|Anomalous diffraction approximation| abs(m-1) very small| x large |  | [Anomalous diffraction approximation](http://en.wikipedia.org/wiki/Anomalous_Diffraction_Theory) | [ADT](http://code.google.com/p/scatterlib/wiki/ADT)|
|Rayleigh-Gans| abs(m-1) very small| any x | close to 1|  |  |
|Complex Angular Momentum| moderate m | large x |  |  |[CAM](http://code.google.com/p/scatterlib/wiki/wiscombe_mieapx.zip)|


## References ##
A. A. Kokhanovsky,  and E. P. Zege, Optical properties of aerosol particles: A review of approximate analytical solutions, Journal of Aerosol Science,  Volume 28, [Issue 1](https://code.google.com/p/scatterlib/issues/detail?id=1), January 1997, Pages 1-21
doi:10.1016/S0021-8502(96)00058-4.

H.C. van de Hulst, Light Scattering by Small Particles, Wiley, New York (1957).