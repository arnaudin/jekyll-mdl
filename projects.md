---
layout: page
title: Projects
permalink: /projects/
---
But it's not who you are underneath... it's what you do that defines you. Death does not wait for you to be ready! Death is not considerate of fair! And make no mistake, here you face death. Tiger. Jujitsu. Panther. You're skilled. But this is not a dance. And you are afraid.

<div class="page-content">
  <div class="mdl-grid">
  
<ul>
  {% for post in site.posts %}
  {% if post.layout == "project"  %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
	{% endif %}
  {% endfor %}
</ul>

</div>
</div>
