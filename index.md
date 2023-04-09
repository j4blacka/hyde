---
layout: default
title: "2023 Western Loudoun Art and Studio Tour"
---
<script src="/js/jquery/jquery.cycle2.js"></script>

<div id="fb-root"></div>
<script>(function(d, s, id) {
  var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) return;
  js = d.createElement(s); js.id = id;
  js.src = "//connect.facebook.net/en_US/sdk.js#xfbml=1&version=v2.0";
  fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'facebook-jssdk'));</script>

<!-- page specific styles -->
<style type="text/css">
#visitorComments ul {list-style-type:none;text-align:left;margin-left:0;margin-left: 1.5em;text-indent: -1.5em;}
#visitorComments ul li:before {
    content: "“";
    color: #9933cc;
    font-family: verdana, sans-serif;
    font-size: 1.5em;
    line-height: 10px;
    vertical-align: middle;
    font-weight: bold;
    padding-right: 0.2em;
    width: 1.5em;
    opacity: 0.66;
}
#visitorComments ul li:after {
    content: "”";
    color: #9933cc;
    font-family: verdana, sans-serif;
    font-size: 1.5em;
    line-height: 10px;
    vertical-align: middle;
    font-weight: bold;
    padding-left: 0.2em;
    width: 1.5em;
    opacity: 0.66;
}
#visitorComments ul li {list-style-type:none; min-height:14px;padding-left:0px;margin-bottom:5px;}
#missionStatement {font-size:0.9em;padding:0.75em 1.5em;border:solid 0.90em #A9D1E8;}
#missionStatement h3 {margin:0.25em 0;xpadding:0;}

.cycle-slideshow {min-height:15em;}
.cycle-slideshow div.studio {width:100%;margin:auto;}
.cycle-slideshow div.studio figure img {width:100%;height:auto;background:red;
}
.cycle-slideshow div.studio figure {min-height:276px;}
.cycle-slideshow div.studio figcaption {
    background: white;
}
/* pager */
.cycle-pager {
    text-align: center; width: 100%; z-index: 500; position: absolute; top: 215px; overflow: hidden;
}
.cycle-pager span {
    font-family: arial; font-size: 50px; width: 20px; height: 16px;
    display: inline-block; color: #ddd; cursor: pointer;
}
.cycle-pager::selection {
    background: red;
}
.cycle-pager span.cycle-pager-active { color: #D646CF; color:#9933cc;}
.cycle-pager > * { cursor: pointer;}

@media screen and (min-width: 783px) {
	.fb-like-box {left:20px;}
}

@media (max-width: 767px) {
	.cycle-pager {top: 200px;}
}
@media (max-width: 400px) {
	.cycle-pager {top: 460px;display: none !important;}
	.cycle-slideshow div.studio p {padding-left:60px;}
	.cycle-slideshow div.studio p:first-child {
		background: red;
		min-height: 75px;
		padding: 20px 0 0 50px;
		background-size: 40px;
	}
	.hide-on-pocket-mobile {
		display: none !important;
	}
}
</style>


<div class="entry-content">
	<p style="text-align:center">
		<strong>Please join us for the 16th Annual Western&nbsp;Loudoun&nbsp;Art&nbsp;&amp;&nbsp;Studio&nbsp;Tour<br> The tour will be held June&nbsp;2,&nbsp;3&nbsp;&amp;&nbsp;4,&nbsp;2023 — Friday, Saturday &amp; Sunday, 10:00am&nbsp;-&nbsp;5:00pm!</strong><br/>
		</p>{% comment %}<br/>
		<span style="color: #9933cc;font-size:1.5em;"><strong>Thank you to everyone who participated in the 15th annual tour! </strong><br><br><strong>We can't wait to see you in 2023!</strong></span><br />

<span style="font-size:1.5em;color:#8a59ab;display:inline-block;margin-top:0.5em;"> Call for Entries</span> <br />
		Applications from eligible artists for the 2023 Tour will be accepted at <a href="https://artist.callforentry.org/festivals_unique_info.php?ID=11026">www.callforentry.org</a> from November 1, 2022, to January 31, 2023.</p>
{% endcomment %}

<hr noshade="noshade" size="4">

<div style="max-width:672px;">
	<div class="cycle-slideshow" data-cycle-fx="fade" data-cycle-timeout="6000" data-cycle-pause-on-hover="true" data-cycle-slides="> div">
		<div class="studio">
			<figure>
				<img alt="Kristen Swanson's White House Ceramic Studios" src="/artists/slide-show/Kristin-Swanson_5x2.jpg" width="640">
				<figcaption style="text-align:center;display:block;">
					<small>Kristen Swanson's White House Ceramic Studios</small>
				</figcaption>
			</figure>
		</div>
		<div class="studio">
			<figure>
				<img alt="Don Maloney working on woodturning at Artistic Woodturnings" src="/artists/slide-show/Don-Maloney_5x2.jpg" width="640">
				<figcaption style="text-align:center;display:block;">
					<small>Don Maloney at the Maloney's studio, Artistic Woodturnings</small>
				</figcaption>
			</figure>
		</div>
		<div class="studio">
			<figure>
				<img alt="Carol Clay-Ward's studio" src="/artists/slide-show/ClayWard_5x2.jpg" width="640">
				<figcaption style="text-align:center;display:block;">
					<small>Carol Clay-Ward's studio</small>
				</figcaption>
			</figure>
		</div>
		<div class="studio">
			<figure>
				<img alt="Eric Scott's studio" src="/artists/slide-show/DeMark_5x2.jpg" width="640">
				<figcaption style="text-align:center;display:block;">
					<small>The DeMark's studio</small>
				</figcaption>
			</figure>
		</div>
		<div class="studio">
			<figure>
				<img alt="Art at Garden Corner" src="/artists/slide-show/GardenCorner_5x2.jpg" width="640">
				<figcaption style="text-align:center;display:block;">
					<small>Art at Garden Corner</small>
				</figcaption>
			</figure>
		</div>
		<p class="cycle-pager">
		</p>
	</div>
	<figure>
		<a href="/studios.html"><img alt="Inside some artists' workspaces" src="/assets/images/banner-studio-interiors.jpg" width="672"></a>
		<figcaption style="text-align:center;display:block;">
			<small><a href="/studios.htm" class="unDecoratedLink" style="text-decoration: none;display:inline-block;">Click to see more snapshots of artists' studios</a></small>
		</figcaption>
	</figure>
	<p>
		<big>Free and open to the public</big>
	</p>
	<p>
		The Western Loudoun Art and Studio Tour offers a weekend of art, shopping, and relaxation. Meet more than 40 talented <a href="/artists.htm">artists</a> as you wind through the scenic countryside and historic villages of western Loudoun County. Enjoy paintings, pottery, jewelry, photography, fiber, sculpture, and more!
	</p>
</div>
<div class="grid-container grid-parent">
	<div class="grid-60 grid-parent">
		<div style="padding-right:20px">
			<p>
				Presented by <a href="http://www.franklinparkartscenter.org" target="_blank">Franklin Park Arts Center</a>, <a href="http://www.roundhillartscenter.org/" target="_blank">Round Hill Arts Center</a>, and <a href="http://www.franklinparkartscenter.org/" target="_blank">The Friends of Franklin Park Arts Center</a>.
			</p>
		</div>
	</div>
	<div class="grid-40 grid-parent" style="border: 2px solid black; padding: 1em;">
		<p>
			Learn about the <a href="/artists.htm">artists</a> and <a href="/map.htm">map your route</a> online.
		</p>
	</div>
</div>
<div class="clear">
</div>
<p>
	&nbsp;
</p>
<div id="missionStatement">
	<h3>
		Mission:
	</h3>
	<p>
		To help promote Loudoun County as a scenic and cultural destination<br> by producing a tour of our county’s visual artists to celebrate their work and<br> to provide an educational experience for the public.
	</p>
	<h3>
		Goals:
	</h3>
	<p>
		For Visitors
	</p>
	<ul>
		<li>Visitors experience personal interaction with professional artists and have the opportunity to view their work processes</li>
		<li>Visitors are given an opportunity to visit and support our artists</li>
		<li>Visitors experience Loudoun’s other attractions, restaurants, wineries, and shopping opportunities</li>
	</ul>
	<p>
		For Artists
	</p>
	<ul>
		<li>Artists promote and offer their work for sale in a studio setting</li>
		<li>Artists demonstrate their value as a cultural and economic resource for Loudoun County</li>
		<li>The Studio Tour serves as a vehicle to bring the Loudoun County visual arts community together</li>
	</ul>
	<p>
		For the Community
	</p>
	<ul>
		<li>The Studio Tour becomes an annual tradition</li>
		<li>The Studio Tour is recognized as a significant event in helping to brand western Loudoun County as an arts destination</li>
	</ul>
</div>
<p>
	&nbsp;
</p>
<div class="grid-container">
	<div class="grid-50">
		<div id="visitorComments">
			<h2>
				<span style="display:block;font-size:1.25em;">Visitor comments</span> about previous tours
			</h2>
			<ul>
				<li>Loved the Tour!</li>
				<li>Lots of fun!</li>
				<li>The artists are always so informative and a pleasure to talk with.</li>
				<li>Great seeing art where it’s created.</li>
				<li>Thoroughly enjoyed the day. It is so nice of the artists to share their talents with us.</li>
				<li>Enjoyed meeting the artists and seeing W. Loudoun County.</li>
				<li>Wow! So much talent!</li>
				<li>Great way to meet local artists and see their work.</li>
				<li>I can’t believe all these amazing artists moved to one local area!</li>
				<li>Can’t wait till next year!</li>
			</ul>
			<div class="clear">
			</div>
		</div>
	</div>
	<div class="grid-50">
		<div class="fb-like-box" data-href="https://www.facebook.com/wlast" data-colorscheme="light" data-show-faces="false" data-header="true" data-stream="true" data-show-border="true">
		</div>
	</div>
</div>
<hr style="clear:both;height: 4px;background-color:#999;">
<p>
	<a href="/volunteer.html"><img class="alignright" src="/assets/images/callout-volunteer-with-the-tour.gif" alt="Volunteer with the Tour" width="175" height="178"></a>
</p>
<p>
	&nbsp;
</p>
<p>
	<a title="Volunteer" href="/volunteer.html">Volunteering with the Tour</a> is a great way to <a title="Tour Sponsors" href="/volunteer.html">show your support</a> for the visual arts!
</p>
</div>

{% include sponsors-logos.html %}

{% include support-the-tour.html %}

{% include get-merchandise.html %}
