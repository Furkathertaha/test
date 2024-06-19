## Notes for APIC and MPM

The transfer from particles to grid is motivated analogously to the piecewise rigid case and is of the form

$$ m_i^n \mathbf{v} _i^n = \sum _{p} w _{ip}^n m_p \left( \mathbf{v}_p^n + \mathbf{B}_p^n \left( \mathbf{D}_p^n \right)^{-1} \left( \mathbf{x}_i - \mathbf{x}_p^n \right) \right), \quad (8) $$

where $$\mathbf{C}_p^n = \mathbf{B}_p^n \left( \mathbf{D}_p^n \right)^{-1}$$ and $$\mathbf{D}_p^n$$ is analogous to an inertia tensor. $$\mathbf{D}_p^n$$ is given by

$$ \mathbf{D} _p^n = \sum _{i} w _{ip}^n \left( \mathbf{x}_i - \mathbf{x}_p \right) \left( \mathbf{x}_i - \mathbf{x}_p \right)^T $$

and is derived by preserving affine motion during the transfers. The corresponding transfer from the grid back to particles is

$$ \mathbf{B} _p^{n+1} = \sum _{i} w _{ip}^{n+1} \mathbf{v}_i^n \left( \mathbf{x}_i - \mathbf{x}_p \right)^T. \quad (10) $$


<!--
# Games201 Notes

For PK1 stress, it has the definition that $$[df]=[PK_1] \circ [n_0] \cdot dA_0$$ on a give surface with respect to initial rest state.

Meanwhile, for the same surface, $$dE = \vec{df} \cdot \vec{dx},$$ so $$[df] = [\frac{\partial E}{\partial F}] \circ [\frac{\partial F}{\partial x}]=dV_0 \cdot [PK_1] \circ [\frac{\partial F}{\partial x}].$$

Does $$[n_0] \cdot dA_0 = dV_0 [\frac{\partial F}{\partial x}] ~~~~ (1) ~~~ ?$$

$$[L]=[F][L_0] ~~ and ~~ [L']=[F'][L_0] \rightarrow [dL]=[dF][L_0]$$

$$[dL]=[dF][L_0]=[\frac{\partial F}{\partial x}][dx]^\mathsf{T}[L_0]$$

However, it should hold that $$[dL] = [dx],$$ thinking about the surface deformation difference should the same as surface position displacemnet.

So $$[\frac{\partial F}{\partial x}] = \frac{[dx]}{\vec{dx}\cdot\vec{L_0}}.$$

When $$dV_0/dA_0 = |L_0| ~~~~ ([L_0]=|L_0|[n_0]$$ so that it gives correct volume), only if $$[dx]$$ in the same direction as $$[n_0]$$ can (1) holds,  think about why? One cue might be that the surface direction can be chosen arbitrarily, but solely for $$dE=\vec{df}\cdot\vec{dx}$$ has no indication for surface direction (the same force and displacement can resulte the same amount of work regardless which surface direction it is rotated), then it is somehow specific.
-->



<!--
# SPACE STYLE DRAGON SCENE ANIMATION

A WebGL-based Chinese dragon animation with STL loader and GLSL shader imposed via Three.js. 

## Table of Contents

- [Features](#features)
- [Dependency](#dependency) 
- [Demo](#demo)
<!-- - [Usage](#usage) -->
<!-- [Contributing](#contributing) -->
<!-- [License](#license) -->
<!-- [Acknowledgements](#acknowledgements) -->

<!--
## Features

- webGL-based 3D rendering
- STL model loader
- ShaderFrog and GLSL-type shaders
- three.js for web3D
- Mathematically formulated dynamic shader
- parametrized 3D curve animation

## Dependency

* three.js r71

* shaderfrog-runtime.min.js

* STLLoader.js

### Standard
* ES6 


## Project 
[https://furkathertaha.github.io/assets/threeJS/sf/long2.html](https://furkathertaha.github.io/assets/threeJS/sf/long2.html)

## THREE.js code 
[https://furkathertaha.github.io/assets/threeJS/sf/test2.js](https://furkathertaha.github.io/assets/threeJS/sf/test2.js)
## GL shader code (GLSL)

[Dragon head & tail](https://furkathertaha.github.io/assets/threeJS/sf/MeronSoda_s_BRDF.json) &emsp;
[Dragon body](https://furkathertaha.github.io/assets/threeJS/sf/MeronSoda_s_BRDF_copper.json) &emsp;
[Dragon claw](https://furkathertaha.github.io/assets/threeJS/sf/MeronSoda_s_BRDF_red.json) &emsp;
[Star1](https://furkathertaha.github.io/assets/threeJS/sf/Fork_of_New_Composed_Shader.json) &emsp;
[Star2](https://furkathertaha.github.io/assets/threeJS/sf/Sun.json) &emsp;
[Background](https://furkathertaha.github.io/assets/threeJS/sf/Star_Field.json) &emsp;
[Cosmic dust](https://furkathertaha.github.io/assets/threeJS/sf/dash/0.json) &emsp;

[Robotic metal](https://furkathertaha.github.io/assets/threeJS/sf/Funny_Bunny.json)

## models (STL)
[Dragon Head](https://furkathertaha.github.io/assets/threeJS/sf/tou.stl) $~~~$
[Dragon Body](https://furkathertaha.github.io/assets/threeJS/sf/bodyy.stl) $~~~$
[Dragon Claw](https://furkathertaha.github.io/assets/threeJS/sf/jiao.stl) $~~~$
[Dragon Tail](https://furkathertaha.github.io/assets/threeJS/sf/wei.stl)
## textures (png)
[Cosmic Dust](https://furkathertaha.github.io/assets/threeJS/sf/thumb_contrast-noise.png)

## Video (mp4)
[screengrab1](https://furkathertaha.github.io/assets/videos/long2.mp4) `   `
[screengrab2](https://furkathertaha.github.io/assets/videos/long1.mp4)

## Presentation (pdf)
[presentation]() `   `
[document]()
##

<span style="font-size: 20px;">[My GitHub Projects!](https://github.com/Furkath)</span>

<a style="font-size: 30px;" href="https://github.com/Furkath">My GitHub Projects!</a>

<font size = '3'> [My GitHub Projects!](https://github.com/Furkath) </font>
 
## Demo

![try](https://github.com/Furkathertaha/personal_cdn/blob/main/l2.gif)

&nbsp; <img src="https://github.com/Furkathertaha/personal_cdn/blob/main/l2.gif" alt="demo1" width="480"  /> `   ` <img src="https://github.com/Furkathertaha/personal_cdn/blob/main/l1.gif" alt="demo2" width="480"  /> 

-Screen Shots:

&emsp; &emsp;  &emsp; &emsp; <img src="https://github.com/Furkathertaha/personal_cdn/blob/main/l2.png" alt="demo3" width="400" />  `     `   <img src="https://github.com/Furkathertaha/personal_cdn/blob/main/l1.png" alt="demo4" width="400"  />
-->
