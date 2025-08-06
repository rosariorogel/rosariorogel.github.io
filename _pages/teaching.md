---
layout: single
title: Teaching
subtitle: Classes, workshops, webinars, and more
permalink: teaching
header:
  image: /assets/img/banner_teaching3.jpg
---
<div style="background-color: #fff9e6; border-left: 4px solid #f0ad4e; padding: 1em; margin-bottom: 1em;">
  <strong>Note:</strong> This section shows the different sessions for each course or workshop. To view all available sessions, place your cursor over the upper right corner of the video box and click on the playlist icon.
</div>

---

<div class="row">
{% for p in site.data.playlists %}
  <div class="col-md-6 mb-4">
    <h3>{{ p.name }}</h3>
    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; margin: auto;">
      <iframe
        src="https://www.youtube.com/embed?listType=playlist&list={{ p.id }}"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
        style="position: absolute; top:0; left:0; width:100%; height:100%;"
      ></iframe>
    </div>
  </div>
{% endfor %}
</div>

  
