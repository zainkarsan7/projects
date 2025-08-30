---
layout: page
permalink: /teaching/
title: teaching
description: Materials for courses you taught. Replace this text with your description.
nav: true
nav_order: 6
---

<details>
  <summary>Click to expand</summary>
  <div markdown="1">
  - This works inside Markdown.
  - No JavaScript required.
  - Great for simple notes.
  </div>
</details>


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include video.liquid path="assets/img/tinyz/5ax_out.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        5 axis variant of the machine with a custom post developed in MasterCAM. The challenge to keep the B + C axes as small as possible meant integrating a custom spindle assembly with the body of the B axis.   
    </div>
</div>

<div class="post">
  <header class="post-header">
    <h1 class="post-title">{{ page.title }}</h1>
    <p class="desc">{{ page.subtitle }}</p>
  </header>

  <article>
    <div class="table-responsive">
      <table class="table table-striped table-hover">
        <thead>
          <tr>
            <th>#</th>
            <th>Title</th>
            <th>Year</th>
            <th>Tags</th>
            <th>Details</th>
          </tr>
        </thead>

        <tbody>
        {% assign i = 0 %}
        {% for e in site.projects %}
          {% assign i = i | plus: 1 %}
          <tr>
            <td>{{ i }}</td>
            <td>{{ e.title }}</td>
            <td>{{ e.year }}</td>
            <td>
              {% if e.tags %}
                {% for tag in e.tags %}
                  <span class="badge badge-pill badge-light small">{{ tag }}</span>
                {% endfor %}
              {% endif %}
            </td>
            <td>
              <button class="btn btn-sm btn-outline-primary" 
                      type="button" 
                      data-toggle="collapse" 
                      data-target="#collapse{{ i }}" 
                      aria-expanded="false" 
                      aria-controls="collapse{{ i }}">
                Show
              </button>
            </td>
          </tr>
          <tr class="collapse-row">
            <td colspan="5" class="p-0 border-0">
              <div class="collapse" id="collapse{{ i }}">
                <div class="card card-body">
                  {% if e.description %}
                    <p>{{ e.description }}</p>
                  {% endif %}
                  {% if e.extra %}
                    <p><strong>Extra:</strong> {{ e.extra }}</p>
                  {% endif %}
                </div>
              </div>
            </td>
          </tr>
        {% endfor %}
        </tbody>
      </table>
    </div>
  </article>
</div>
