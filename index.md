---
layout: home
title: Lens by HTML5 UP with Instagram via PPI
---

<!-- Thumbnail -->
<section id="thumbnails">{% for img in site.data.images %}
	<article>
		<a class="thumbnail" href="{{ img.image }}" data-position="left center"><img src="{{ img.image_small }}" alt="" /></a>		
		<p>{{ img.caption }}</p>
		<p><a href="{{ img.permalink }}">View on Instagram</a></p>
	</article>
{% endfor %}</section>
