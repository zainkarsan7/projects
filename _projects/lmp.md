---
layout: page
title: Liquid Metal Printing
description: Metal AM at Self Assembly Lab
img: assets/img/lmp/1.png
importance: 1
category: work
related_publications: true
---

This work was developed as a student researcher at the Self Assembly Lab as part of a dual degree in computational design and mechanical engineering. Liquid Metal Printing is a rapid, low cost, large scale and low resolution printing method involving rapid injection of molten metal into a bed of glass bead along a predetermined path. This work was done in collaboration with Kimball Kaiser, and focues on transitioning the existing machine which could melt and print with pewter, into a machine that could melt and print aluminum.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/img/lmp/process_snip_out.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/lmp/chair_1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/lmp/chair_2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/lmp/chair_3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/lmp/chair_4.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Chair designs, printed flat, bent into shape, with machined hardwood maple seats and backs. 
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/lmp/Nozzles.png" title="Nozzle Prototypes, turned copper" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Several nozzles were designed, fabricated and tested, and their thermal properties modelled and validated experimentally. 
</div>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/lmp/Nozzles_temp_response.png" title="nozzle thermal response" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/lmp/Temperature_Response_Validation.png" title="nozzle thermal response" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/lmp/Wire_Feed_Rig_Side.JPG" title="wirefeed" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        The numerical simulations shown here are implemented in Matlab using simplified geometry, and solve the poisson equation over an annular polar domain. The nozzle tip temperature response is plotted here, and validated experimentally using the setup shown here. Different feed stock strategies were also tested. In this setup, we tested drawn wire spools.
    </div>
</div>
Characterizing the fluid flow was another critical part of the project, especially as a means for developing control strategies and yielding more repeatable prints. The process is modelled in this diagram, with relevant parameters identified for use with various fluid flow models including Torricelli and Stokes flow.  

<div class="row justify-content-sm-center">
    <div class="col-sm-9 mt-3 mt-md-0">
        {% include video.liquid path="assets/img/lmp/Stopper_Flow.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
    <div class="col-sm-3 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/lmp/fluid_diag.jpg" title="wirefeed" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include video.liquid path="assets/img/lmp/thermal_clip.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        Thermal imaging was proposed as a way to provide feed back during a print.
    </div>
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/lmp/Torricelli_1.png" title="wirefeed" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include video.liquid path="assets/img/lmp/furnace_out.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        Building a small scale furnace which could be attached to a moving gantry comprised the hardware side of the project, which would enable printing at higher temperatures. Several designs were explored alongside suitable crucible and nozzle designs. The corrosivity of molten aluminum led to repeated experiments with different combinations of turned stainless steel, titanium and ceramic.
    </div>
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include video.liquid path="assets/img/lmp/nozzle_assy_out.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        Building a small scale furnace which could be attached to a moving gantry comprised the hardware side of the project, which would enable printing at higher temperatures. Several designs were explored alongside suitable crucible and nozzle designs. The corrosivity of molten aluminum led to repeated experiments with different combinations of turned stainless steel, titanium and ceramic.
    </div>
</div>

