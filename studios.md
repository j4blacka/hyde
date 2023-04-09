---
layout: default
title: "Studio Photos"
---
<h1>{{page.title}}</h1>
<div class="entry-content">
	<div id="wrapper">
	<div style="margin:auto;">
		<div style="max-width:38rem;">
			<p>Visiting an artist's studio can be educational or inspirational, or both!</p>
			<p>Artists in this year's tour do their work in places that range from purpose-built studio and gallery spaces to tiny but efficient spaces carved out of the artist's home.</p>
		</div>
	</div>

stops ?
<ol>
{% for artist in site.data.basics %}
	{% assign thisStop =  artist.StopNo %}
	<li>Tour Stop: {{thisStop}}</li>
{% endfor %}
</ol>
<hr/>
cluster	stop	first_name	last_name

images

{% for stop in site.data.stops %}
show stop #, artist name, link to artist page
then show images

{% for image in site.data.images %}

		{% if image.thumbnail == 'e' or image.thumbnail == 'i' or image.thumbnail == 'ap' %}

			<p id="{{image.filename}}" class="col-sm-9">
				{% assign linkFName = image.first_name | replace:'.','' | replace:' ','-' %}
				{% assign linkLName =  image.last_name | replace:'.','' | replace:' ','-' %}
				<a href="/assets/photos/{{image.filename}}"><img src="/assets/photos/{{image.filename}}" alt="&copy; {{image.first_name}} {{image.last_name}} image {{image.year}}"></a><br/>
				<div class="caption col-sm-10">
					<a href="/artists/{{ linkFName }}-{{ linkLName }}_2023.html">{{image.first_name}} {{image.last_name}}</a>
					{% if image.medium %}{{ image.medium }}: {% endif %}
					{% if image.title %}{{ image.title }}<br />{% endif %}
					{{ image.title }}
					{% if image.description %}<br />{{ image.description }}{% endif %}
				</div>
			</p>

		{% endif %}

{% endfor %}


{% endfor %}
	</div>
</div>
