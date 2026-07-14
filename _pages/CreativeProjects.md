---
title:
layout: default
permalink: /CreativeProjects/
published: true
---


<div class="CProjectContainer">

	<div class="gallery">


  {% for Cproject in site.CreativeProjects %}

  {% if Cproject.redirect %}
  <div class="CprojectTile">
          <a href="{{ Cproject.redirect }}" target="_blank">
          <span>
              <h2>{{ Cproject.title }}</h2>
              <br/>
              <p>{{ Cproject.description }}</p>
          </span>
          </a>
  </div>

  {% else %}

  <div class="CprojectTile">
          <a href="{{ Cproject.url | prepend: site.baseurl }}">
          <span>
              <h2>{{ Cproject.title }}</h2>
              <br/>
              <p>{{ Cproject.description }}</p>
          </span>
          </a>
  </div>

  {% endif %}

  {% endfor %}

	</div>

</div>
