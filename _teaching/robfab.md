---
layout: page
title: Robotic Fabrication
description: 4.453 Creative Machine Learning 
img: assets/img/rob_fab/rob_fab_banner.JPG
importance: 2
category: work
giscus_comments: true
---

<div class="row">
{% include video.liquid path="assets/img/deskmate/deskmate_out.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
</div>

This project involved developing a simple drawing machine and a vision based ML pipeline to actuate the machine in response to user input. We typically interface with generative AI and its output through software, without a corresponding physical embodiement. This project proposed to embed an intelligent drawing assistant inside a commonly used tool for a designer, trace paper.  

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/deskmate/axon.jpg" title="axo" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
           The drawing machine uses a roll of trace paper as the canvas with the possibility to draw continuously along the scroll up to 50 yards. 
    </div>
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/deskmate/hand_tracking.jpg" title="axo" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
           Initially, a hand tracking setup was implemented to test the machine response to user interaction.
    </div>
</div>


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/deskmate/latent_walk.gif" title="axo" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        Two models were used, the first shown here is a VAE encoding RGB images into a high dimensional latent space. Here are some samples from quaternion slerp-ing through the latent space.  
    </div>
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/deskmate/rnn_latent.png" title="axo" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        Another approach involved using vector based data in an RNN model, as implemented in Sketch-RNN. 
    </div>
</div>

