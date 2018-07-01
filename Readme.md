# A-Frame Three Color Gradient Shader

Modified shader from: https://github.com/zcanter/aframe-gradient-sky/blob/master/README.md

## Demo

https://aframe-three-color-shader-demo.glitch.me/

<!-- View Source Button -->
<a href="https://glitch.com/edit/#!/aframe-three-color-shader-demo">
  <img src="https://cdn.glitch.com/2bdfb3f8-05ef-4035-a06e-2043962a3a13%2Fview-source%402x.png?1513093958802" alt="view source button" aria-label="view source" height="33">
</a>

<!-- Remix Button -->
<a href="https://glitch.com/edit/#!/remix/aframe-three-color-shader-demo">
  <img src="https://cdn.glitch.com/2bdfb3f8-05ef-4035-a06e-2043962a3a13%2Fremix%402x.png?1513093958726" alt="remix button" aria-label="remix" height="33">
</a>

## Usage

---
    <script src="https://unpkg.com/@tlaukkan/aframe-three-color-gradient-shader@0.0.1/index.js"></script>

    ...

    <a-sky geometry="primitive: sphere" material="shader: threeColorGradientShader; topColor: #D57500; middleColor: #4E6172; bottomColor: #000000;offset: 0.0"></a-sky>
---

## Publish package

### First publish

---
    npm publish --access public
---

### Update

---
    npm version patch
    npm publish
---