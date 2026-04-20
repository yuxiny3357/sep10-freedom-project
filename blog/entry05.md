# Entry 5
##### 4/20/26

## Context
During the past few weeks we were learning how to use our tools, my tool was aframe. I tinker with it learning how to make shapes using the shapes. I also figure out how to do the lighting and explore how to make 360 images.

## Sources
I used A-Frame website and youtube videos to research and learn how make different shapes.

* [A-frame school](https://aframe.io/aframe-school/#/)
* [youtube video](https://youtu.be/XFv55TajSAg?si=OPH0Rs8n21gdkFyH)
* [ Aframe 360 image ](https://aframe.io/docs/1.7.0/guides/building-a-360-image-gallery.html)
* [Aframe lighting](https://aframe.io/docs/1.7.0/components/light.html#configuring_shadows_shadowcameraleft)

##  Examples

Starter code for lighting
```Html
   <a-scene>
      <a-sphere position="0 1.77 -2 " radius="1.1" color="#EF2D5E"></a-sphere>
      <a-cylinder position="0 1.75 -2" radius="0.5" height=".5" color="#FFC65D"></a-cylinder>
      <a-plane position="0 0 -4" rotation="-50 10 0" width="3" height="3" color="#7BC8A4"></a-plane>
      <a-sky color="#27F2F5"></a-sky>
     <a-light type="directional"></a-light>

 ```
 This made the whole cricle black, i played with the directional and the way the light hits the cricle

 End result
 ```HTML
           <a-scene>
      <a-sphere position="0 1.77 -2 " radius="1.1" color="#EF2D5E"></a-sphere>
      <a-cylinder position="0 1.75 -2" radius="0.5" height=".5" color="#FFC65D"></a-cylinder>
      <a-plane position="0 0 -4" rotation="-50 10 0" width="3" height="3" color="#7BC8A4"></a-plane>
      <a-sky color="#27F2F5"></a-sky>
     <a-light type="directional" position="1 1 1" rotation="-45 6 100" target="#directionaltarget">
  <a-entity id="directionaltarget" position="0 0 -1"></a-entity>
</a-light>
    </a-scene>
```

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
