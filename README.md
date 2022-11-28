# Houdini bakes attributes to PNG files

## System requirement: 
Develop and tested on Houdini Indie 19.5

## For what?
I need a pipeline to bake P (positions) and Cd (colors) attributes to PNG files and then import them to three.js for websites use. This Houdini file can converts mash to particles and bakes the P to `p_16bit.png` and Cd to `color.png`

![A samlpe of p_8bit.png](png-export/box/p_8bit.png)
![A samlpe of color.png](png-export/box/color.png)

## Houdini screens preview
![](previews/screen-preview-01.jpg)
![](previews/screen-preview-02.jpg)
![](previews/screen-preview-03.jpg)

## Three.js app
I created this [threejs code](https://github.com/rc-bellergy/threejs-particles-from-png) that can decode the PNG files and convert the data to particles.

![](previews/threejs-preview.jpg)
