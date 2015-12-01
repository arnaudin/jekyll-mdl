---
layout: page
title: Blog
permalink: /blog/
---
All of my blog posts are listed here. You can follow along via [RSS](../blogfeed.xml "Blog feed"), or on Medium.

Wide text hack. Wide text hack. Wide text hack. Wide text hack. Wide text hack. Wide text hack. Wide text hack. Wide text hack. Wide text hack. Wide text hack. Wide text hack. Wide text hack. Wide text hack. Wide text hack. Wide text hack. Wide text hack. 

<div class="page-content">
<div class="mdl-grid">
	<ul>
	  {% for post in site.categories.blog %}
		<li>
		  <a href="{{ post.url }}">{{ post.title }}</a>
		</li>
	  {% endfor %}
	</ul>
</div>
</div>
