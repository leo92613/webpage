---
layout: post
title:  "Holojam Archive"
date:   2015-10-31 12:00:00


---


# **HOLOJAM!!!!**

This is awesome! This is AWESOME!! THIS IS AWESOME!!!

And look at this INTERVIEW HERE!

<iframe src="https://player.vimeo.com/video/153230708" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

NOT ENOUGH? LOOK AT THIS ONE!

<iframe width="640" height="360" src="https://www.youtube.com/embed/hIO0ZMMhvWI" frameborder="0" allowfullscreen></iframe>

WANT IT? GET THE SDK!!!

[SUPER AWESOME HOLOJAM SDK IS HERE](https://github.com/futurerealitylab/Holojam)


{% for person in site.people %}
  {%if person.title == "Wenbo Lan" %}
  <li>
      <a class="post-link" href="{{ person.url }}">{{ person.title }}</a>
  </li>
  {% endif %}
{% endfor %}
