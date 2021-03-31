# Diffraction Simulations - Angular Spectrum Method

Implementation of the angular spectrum method in Python to simulate diffraction patterns with arbitrary apertures. You can use it for simulating both monochromatic and polychromatic light also with arbitrary spectrums.

How the method and the simulator work is described in this [Article](https://rafael-fuente.github.io/simulating-diffraction-patterns-with-the-angular-spectrum-method-and-python.html). Take a look to the [Youtube video](https://youtu.be/Ft8CMEooBAE) to see the animated simulations!

[![animation](/images/diffraction_animated.gif)](https://www.youtube.com/watch?v=Ft8CMEooBAE)


## Installation
```
pip install diffractsim
```

Alternatively, to download the examples and the apertures as well, you can also build from source by cloning the repository and running from the main folder project on the command prompt:
```
pip install .
```

## Examples

To perform the simulations, just run from the [examples subdirectory](https://github.com/rafael-fuente/Diffraction-Simulations--Angular-Spectrum-Method/tree/main/examples) the corresponding Python scripts on the command prompt:


```
python hexagon_monochromatic.py
```

![N|Solid](/images/hexagon_monochromatic.png)

```
python hexagon_polychromatic.py
```

![N|Solid](/images/hexagon_polychromatic.png)

```
python rectangular_grating_small.py
```

![N|Solid](/images/rectangular_grating_small.png)

```
python rectangular_grating.py
```

![N|Solid](/images/rectangular_grating.png)

```
python rings.py
```

![N|Solid](/images/rings.png)

```
python text.py
```

![N|Solid](/images/text.png)


For simulating diffraction patterns with lenses, take a look at [these examples](https://github.com/rafael-fuente/Diffraction-Simulations--Angular-Spectrum-Method/blob/main/Simulations%20with%20lenses.md).

