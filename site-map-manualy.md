---
layout: default
title: "Site Map"
---
for page in site.pages
<ol>
	{% for page in site.pages %}
	<li>{{page.url}} <lastmod>{{site.time | date: '%Y-%m-%d' }}</lastmod> </li>
	{% endfor %}
</ol>
for post in site.posts
<ol>
	{% for post in site.posts %} <i>{{post.url}} <lastmod>{{site.time | date: '%Y-%m-%d' }}</lastmod> </li>
	{% endfor %}
</ol>
for page in site.artist
<ol>
	{% for page in site.artist %}
	<li>{{page.url}} <lastmod>{{site.time | date: '%Y-%m-%d' }}</lastmod> </li>
	{% endfor %}
</ol>
for page in site.artists
<ol>
	{% for page in site.artists %}
	<li>{{page.url}} <lastmod>{{site.time | date: '%Y-%m-%d' }}</lastmod> </li>
	{% endfor %}
</ol>

