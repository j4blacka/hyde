---
layout: default
title: "Artist Images (All)"
---
<h1>2023 {{ page.title }}</h1>
<div class="entry-content">
	<div id="artist-wrapper">
		<div class="xthumbnailGallery">

  {% for image in site.data.images %}
  {{ artist.FirstName}} {{artist.LastName }}
  <ul>
    <li id="{{ artist.ID }}" class="thumbnail {{ cluster }} {% if artist.New %} new-artist {% endif %}">
      <div class="artistName"><a href="/artists/{{ artist.name }}_2023.html">{{ artist.FirstName}} {{artist.LastName }}</a></div>
      <div class="photo">
      	<a href="/artists/{{ artist.name }}_2023.html"><img id="photo{{ image.ArtistFairID }}" src="/assets/photos/{{ image.filename }}" alt="{{image.first_name}} {{image.last_name}} {{image.medium}}: {{ image.title }} (c)"></a>
      </div>
      <!--
<div class="media">{{ artist.Media1 }}{% if artist.Media2 %}, {{ artist.Media2 }} {% endif %}</div>
      {% if artist.OpenDays == "Saturday and Sunday Only" %}<small>{{ artist.OpenDays }}</small> {% endif %}
      <p>{{ image.description | markdownify }}</p>
 -->
    </li>
    </ul>
  {% endfor %}

		</div>
	</div>
</div>

<!--
<ul>
  {% for artist in site.artist %}
    <li class="thumbnail">
      <div class="artistName"><a href="/artists/{{ artist.name }}_2023.html">{{ artist.name }}</a></div>
      <div class="media">{{ artist.media }}</div>
      <p>{{ artist.content | markdownify }}</p>
    </li>
  {% endfor %}
</ul>

<hr class="clear" />
 -->

<!--
{% for artist in site.data.basics %}
{{ artist.Cluster }}
{% endfor %}
 -->
