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



**:question:NERF가 풀고자하는 문제와 NERD가 풀고자하는 문제의 가장 큰 차이점은?**

NERF는 환경에 대한 lighting이 고정된 상태에서의 reconstruction을 겨냥했다면, NERD의 경우에는 다양한 lighting환경에서의 물체를 decompose하여 물체의 shape, BRDF, illumination 총 3개의 항목에 대해서 분석하는 문제를 풀고자한다. 이렇게 여러개의 rendering에 필요한 부분들로 쪼개어 extraction하는 것을 inverse rendering이라고 하고 이 문제를 풀고자한다.



