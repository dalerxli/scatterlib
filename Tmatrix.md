# T-matrix codes #

## Barber and Hill scattering by axisymmetric particles (T-matrix method) ##
These codes were published in "Light Scattering by Particles: Computational Methods", P.W. Barber and S.C. Hill, 1990 by World Scientific Publishing. There are nine computer programs
which may be used to calculate the light scattered by nonspherical
particles.  An auxiliary program determines array dimensions for
the nine basic programs.

The source code is available here [barber.zip](http://scatterlib.googlecode.com/files/barber.zip).

| Name|Description|
|:----|:----------|
|T1.for |     convergence test and store T matrix|
|T2.for |     scattering for fixed orientation - use T matrix|
|T3.for |     scattering in all directions for a particle in fixed orientation - use T matrix|
|T4.for |     scattering for 2D random orientation - use T matrix|
|T5.for |     scattering for 3D random orientation - use T matrix|
|T6.for |     scattering matrix calculations - use T matrix|
|T7.for |     scattering efficiency vs size parameter|
|T8.for |     internal intensity distribution - 2D and 3D - use A matrix|
|T9.for  |    external intensity distribution - 2D and 3D - use T matrix|
|dim.for  |   obtain nrank-dependent array dimensions for all programs|