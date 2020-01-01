---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<div align="justify">
I am an undergraduate physics and mathematics student at the University of Nevada, Reno, currently working with Dr. Andrei Derevianko on a dark matter detection experiment using the atomic clock data from GPS satellites (see the <a href="http://www.dereviankogroup.com/">GPS.DM Collaboration</a>). I also work with Dr. Joshua Williams on dissociative electron attachment and photodissociation molecular dynamics experiments. Previously, I have performed exoplanet detection experiments with the <a href="http://www.greatbasinobservatory.org/">Great Basin Observatory</a>. Lastly, I am currently one of the Senior Co-Editors for the Nevada State Undergraduate Research Journal (<a href="http://www.nsurj.com/">NSURJ</a>).
</div>


Recent Posts
======
{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% include archive-single.html %}
{% endfor %}
