# NeRD: Neural Reflectance Decomposition from Image Collections

[project page](https://markboss.me/publication/2021-nerd/) | [github](https://github.com/cgtuebingen/NeRD-Neural-Reflectance-Decomposition)

**Conference:** ICCV 2021

## TL;DR
NERD learns the BRDF parameters (base color, metalic, and roughness) instead of the color at each 3D location. Knowing that similar materials appear on an object, an encoder decoder is trained to compress the BRDF that forces grouping of similar materials. Since this method learns BRDF parameters directly (leverages explicit representations), the rendering is capable in real-time (compared to NERF which takes 30s). This method can handle varing illuminations and relight the object with any light source.


**Authors**

* Mark Boss
* Varun Jampani
* Raphael Braun 
* Ce Liu
* Jonathan T. Barron
* Hendrik P. A. Lensch


**Afiliations**

* University of Tübingen
* Google Research
* Microsoft Azure AI (work done at Google)







