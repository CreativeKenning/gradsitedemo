---
title:
layout: default
permalink: /CreativeProjects/
published: True
---


<div class="ProjectContainer">

	<div class="gallery">


  {% for project in site.CreativeProjects %}

  {% if project.redirect %}
  <div class="CprojectTile">
          <a href="{{ project.redirect }}" target="_blank">
          <span>
              <h2>{{ project.title }}</h2>
              <br/>
              <p>{{ project.description }}</p>
          </span>
          </a>
  </div>

  {% else %}

  <div class="CprojectTile">
          <a href="{{ project.url | prepend: site.baseurl }}">
          <span>
              <h2>{{ project.title }}</h2>
              <br/>
              <p>{{ project.description }}</p>
          </span>
          </a>
  </div>

  {% endif %}

  {% endfor %}

	</div>

</div>
