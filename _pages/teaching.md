---
layout: page
permalink: /teaching/
title: teaching
description: Primary instructor, syllabus author or co-instructor
nav: true
nav_order: 6
---

<div class="post">
  <!-- <header class="post-header">
    <h1 class="post-title">{{ page.title }}</h1>
    <p class="desc">{{ page.subtitle }}</p>
  </header> -->

  <article>
    <div class="table-responsive"> <!-- keeps it nice on small screens -->
      <table class="table table-striped table-hover">
        <thead>
          <tr>
            <th>#</th>
            <th>Title</th>
            <th>Year</th>
            <th>Tags</th>
            <th>More</th>
          </tr>
        </thead>

        <tbody>
        {% assign combined = site.teaching | concat: site.data.teaching %}

        {%- assign sorted = combined | sort: "year" | reverse -%}

        {% assign i = 0 %}
        {% for p in sorted %}
          {% assign i = i | plus: 1 %}
          <tr>
            <td>{{ i }}</td>
            <td>
              <a href="{{ p.url | relative_url }}">{{ p.title }}</a>
              {% if p.description %}
                <div class="small text-muted">{{ p.description }}</div>
              {% endif %}
            </td>
            <td>{{ p.year }}</td>
            <td>
              {% if p.tags %}
                {% for tag in p.tags %}
                  <span class="badge badge-pill badge-light small">{{ tag }}</span>
                {% endfor %}
              {% endif %}
            </td>
            <td class="text-center">
              {% if p.url %}
                <a class="btn btn-sm btn-outline-primary" href="{{ p.url | relative_url }}">View</a>
              {% elsif p.extra %}
                 <button class="btn btn-sm btn-outline-primary" 
                      type="button" 
                      data-toggle="collapse" 
                      data-target="#collapse{{ i }}" 
                      aria-expanded="false" 
                      aria-controls="collapse{{ i }}">
                Show
              </button>
              {% endif %}
            </td>
            </tr>
            {% if p.extra %}
            <tr class="collapse-row">
            <td colspan="5" class="p-0 border-0">
              <div class="collapse" id="collapse{{ i }}">
                <div class="card card-body">
                  
                    <p><strong>Extra:</strong> {{ p.extra }}</p>
                  
                </div>
              </div>
            </td>
            </tr>
            {% endif %} 
        {% endfor %}
        </tbody>
      </table>
    </div>
  </article>
</div>
