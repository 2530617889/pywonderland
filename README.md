# A Tour in the Wonderland of Math with Python

A collection of python scripts that aimed at drawing beautiful figures or animating interesting algorithms in mathematics.

**This repository will be always under construction as there are too many interesting things in math that can be shown by code.**

[![Code Health](https://landscape.io/github/neozhaoliang/pywonderland/master/landscape.svg?style=flat)](https://landscape.io/github/neozhaoliang/pywonderland/master) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT) [![PyPI](https://img.shields.io/pypi/pyversions/Django.svg)]()


## Contents

- [Mandelbrot Set](#mandelbrot-set)
- [Domino Shuffling Algorithm Animation](#domino-shuffling-algorithm-animation)
- [Icosahedral Kaleidoscope](#icosahedral-kaleidoscope)
- [Newton Fractal](#newton-fractal)
- [The E8 Pattern](#the-e8-pattern)
- [The Modular Group](#the-modular-group)
- [Beauty of Roots](#beauty-of-roots)
- [Generalized Penrose Tilings](#generalized-penrose-tilings)
- [Wilson Algorithm Animation](#wilson-algorithm-animation)
- [World War Z in America](#world-war-z-in-america)

---
### Mandelbrot Set
Mandelbrot 集 [[View Code](./src/misc/mandelbrot.py)]

<br>

<p align="center">
<img src="./img/mandelbrot.png"/>
</p>

<br>
[[Back to Top](#contents)]


---
### Domino Shuffling Algorithm Animation
多米诺洗牌算法 [[View Code](./src/domino/)] [[View Gif Animation](./img/dominoshuffling.gif)] [[Wiki](https://en.wikipedia.org/wiki/Aztec_diamond)]

<br>

<p align="center">
<img src="./img/randomtiling.png">
</p>

<br>
[[Back to Top](#contents)]


---
### Icosahedral Kaleidoscope

正二十面体万花筒 [[View Code](./src/misc/kaleidoscope.py)] [[View Webm Animation](./img/kaleidoscope.webm)]

<br>

<p align="center">
<img src="./img/kaleidoscope.png"/>
</p>

<br>
[[Back to Top](#contents)]

---
### Newton Fractal
Newton 迭代分形 [[View Code](./src/misc/newton.py)] [[Wiki](https://en.wikipedia.org/wiki/Newton_fractal)]

<br>

<p align="center">
<img src="./img/newton.png"/>
</p>

<br>
[[Back to Top](#contents)]


---
### The E8 Pattern
李代数 E8 的根系 [[View Code](./src/misc/e8.py)] [<a href="https://en.wikipedia.org/wiki/E8_(mathematics)">Wiki</a>]

<br>

<p align="center">
<img src="./img/e8-pattern.png"br/>
</p>

<br>
[[Back to Top](#contents)]


---
### The Modular Group
模群的基本域 [[View Code](./src/misc/modulargroup.py)] [[Wiki](https://en.wikipedia.org/wiki/Modular_group)]

<br>

<p align="center">
<img src="./img/modulargroup.png"/>
</p>

<br>
[[Back to Top](#contents)]


---
### Beauty of Roots
Littlewood 多项式的根 [[View Code](./src/misc/rootsart.py)] [[Origin](http://www.math.ucr.edu/home/baez/roots/)]

<br>

<p align="center">
<img src="./img/rootsart.png"/>
</p>

<br>
[[Back to Top](#contents)]


---
### Generalized Penrose Tilings
彭罗斯铺砌 [[View Code](./src/misc/penrose.py)] [[Wiki](https://en.wikipedia.org/wiki/Penrose_tiling)]

<br>

<p align="center">
<img src="./img/penrose.gif"/>
</p>

<br>
[[Back to Top](#contents)]


---
### Wilson Algorithm Animation
Wilson 算法 [[View Code](./src/maze/)] [[View Randomized-DFS Animation](./img/dfs.gif)] [[Wiki](https://en.wikipedia.org/wiki/Loop-erased_random_walk)] [[Mike Bostock's Javascript Animation](https://bl.ocks.org/mbostock/11357811)]

currently only runs with Python2.7

<br>

<p align="center">
<img src="./img/wilson.gif"/>
</p>

<br>
[[Back to Top](#contents)]


---
### World War Z in America
模拟僵尸爆发 [[View Code](./src/zombie/)] [[View Webm Animation](./img/zombie.webm)] 

This is an animation, see the video in the above link.

<br>

<p align="center">
<img src="./img/zombie.png"/>
</p>

<br>
[[Back to Top](#contents)]


## Dependencies

Python libs:

+ `numpy`
+ `matplotlib`
+ `scipy`
+ `cairo`
+ `palettable`
+ `tqdm`
+ `numba`
+ `pyglet`
+ `vapory`

Softwares:

+ `ImageMagick`
+ `FFmpeg`
+ `POV-Ray`