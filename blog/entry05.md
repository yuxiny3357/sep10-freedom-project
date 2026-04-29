# Entry 5
##### 4/20/26
<<<<<<< HEAD

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
=======

## Context
Over the past few weeks, we have been learning how to use different digital tools, and I choose my tool as A-Frame. At first, it was a bit challenging to understand how everythingg worked, but as I spent more time experimenting, I became more comfortable with it. I practiced creating different shapes like boxes, spheres, and cylinders, and learned how to adjust their size, position, and rotation within a scene. I also explored how lighting works and how changing the brightness, color, and placement of lights can affect the overall look and mood of a project. In addition, I learned how to use 360 degree images to create more immersive environments where users can look around in all directions, making the experience feel more interactive. Overall, by experimenting and practicing with A-Frame, I was able to improve my understanding of how to build and design simple virtual reality scenes.

## Sources
I used A-Frame website and youtube videos to research and learn how make different shapes.

* [A-frame school](https://aframe.io/aframe-school/#/)
* [youtube video](https://youtu.be/XFv55TajSAg?si=OPH0Rs8n21gdkFyH)
* [ Aframe 360 image ](https://aframe.io/docs/1.7.0/guides/building-a-360-image-gallery.html)
* [Aframe lighting](https://aframe.io/docs/1.7.0/components/light.html#configuring_shadows_shadowcameraleft)

  
## Engineering Design Process

 At this point, I am focusing on planning and designing how my website will look. I am deciding how to organize each section, what the layout should be, where images and text will go, and how users will move through the pages. I am also thinking about the overall design style so the website is clear, creative, and easy to understand. Also including what I learned about using my tool on my own This step helps me turn my ideas into a structured website plan before I start coding it. 

## Skills

For this project, I have improved skills such as researching and creativity, and I am also beginning to build my coding skills.

* Research skills: I improved my research skills by looking up information about my tool A-frame.

* Thinking creatively: I learned how to think creatively by taking what I already knew about shapes and making them to look like other non shapes such as ice cream or stick man

* Learning skills: I had to learn my tool on my own without my teacher telling me how to use my tools. He gave us tips on be brave to play around with the code to see what changes will happen. 
## Next Steps

My next step is to build my website based on my plan. I will use my layout ideas to begin coding the pages and organizing my content. I will include my research, my inventions, and explanations of how they work. I also want to make sure the website is easy to navigate and visually appealing. This step is important because it turns my design ideas into a real, interactive website that presents my project clearly.

>>>>>>> b9c837c15afeb75eb5f235900b02b6c9f6aaa93c

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
