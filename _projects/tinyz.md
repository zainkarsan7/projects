---
layout: page
title: TinyZ
description: A desktop milling machine, developed during the pandemic to support remote making at MIT School of Architecture
img: assets/img/tinyz/Pumpkin.jpg
importance: 2
category: work
giscus_comments: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
    {% include video.liquid path="assets/img/tinyz/trailer_out.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>

This machine was designed around low cost parts and sized in order to maximize working envelope, thereby permitting the greatest flexibility in machining. The choice to use predominantly aluminum profile made assembly very easy, and the machine extremely modular. 
A studio course was developed around this machine, in which students developed their own material processes by hacking the machine. More information on this course can be found <a href="https://www.w3schools.com">here</a>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include video.liquid path="assets/img/tinyz/kit_out.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        Small batch production of the parts of the kit demonstrate the various capacities at the architecture shops, waterjetting, precision machining, and large format routing.
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>

<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
    {% include video.liquid path="assets/img/tinyz/trailer_out.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}    
</div>
</div>

<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
