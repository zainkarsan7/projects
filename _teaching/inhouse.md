---
layout: page
title: In House
importance: 3
category: work
year: 2021
description: "A digital fabrication studio during the pandemic"
tags: ["Machine Design", "Remote Making"]
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/flex_tester/metrology.jpg" title="metro" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

This work was developed with a team of 4 for a course called Fundamentals of Product Design taught by Marty Culpepper at MIT. This course designing, fabricating and validating a product of our own design. Our group chose to develop a flexure characterization machine, capable of characterizing their stiffness in 2 axes. 

Some of the functional requirements for the load cell are listed here:
<div style="margin-top:1em;" >
<iframe src="{{ 'assets/img/flex_tester/FR_table.pdf' | relative_url }}" 
        width="100%" style="border: none;" style="background-color: #ffffff;">
</iframe>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/flex_tester/metrology_side.jpg" title="metrology diagram" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        Our metrology frame involves two load cells and dial indicators from which we extract stiffness readings. The metrology frame id decoupled from the machine stiffness by two compliant mechanisms.  
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/flex_tester/transmission.jpg" title="metrology diagram" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        We designed a worm gear to connect a hand crank to a vertical leadscrew. The leadscrew moves a stage that can put up to 10kN on a specimen with very little torque on the handcrank. 
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
   <div class="column">
    <div>
        {% include figure.liquid loading="eager" path="assets/img/flex_tester/z_dir.jpg" title="z_dir" class="img-fluid rounded z-depth-1" %}
    </div>
    <div>
        {% include figure.liquid loading="eager" path="assets/img/flex_tester/x_dir.jpg" title="x_dir" class="img-fluid rounded z-depth-1" %} 
    </div>
    </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
       Simulations in solidworks were undertaken to verify if our compliant mechanisms would sufficiently decouple the metrology frame from the machine. 
    </div>
</div>


