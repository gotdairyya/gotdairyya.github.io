---
layout: default
title: c.v.
---

pdf version [here](/assets/images/Akbaba-CV.pdf)

### peer-reviewed conference publications

{% include cv_publications.html data=site.data.publications %}
<br>

### peer-reviewed abstracts + workshop papers

{% include cv_publications.html data=site.data.shortpubs %}
<br>

### reports, editor letters, science communication

{% include cv_publications.html data=site.data.otherpubs %}
<br>

### service

{% include cv_publications.html data=site.data.service %}

<br>

### reviewing

{% include cv_publications.html data=site.data.reviewing %}

<br>

### talks

{% include cv_publications.html data=site.data.talks %}

<br>



### teaching

{% assign teaching = site.data.teaching | sort: "year" %}
{% for class in teaching reversed %}
<bold>{{class.role}}</bold>
<span>{{class.course}}</span><br>
<span>{{class.school}}, {{class.semester}}</span>

{% endfor %}

<br>

### non-university teaching

A important aspect of my pedagogical philosophy is to extend my teaching efforts outside of traditional university walls. I do this through workshops and seminars with non-profit organizations and professional groups, reaching a wide range of age groups and communities.

{% assign workshops = site.data.workshops | sort: "year" %}
{% for class in workshops reversed %}
<bold>{{class.title}}</bold>
<span>{{class.organization}}</span><br>
<span>{{class.country}}, {{class.when}}</span>

{% endfor %}

<!-- {% assign workshops = site.data.workshops | sort: "year" %}
{% for class in workshops reversed %}
<bold>{{class.role}}</bold>
<span>{{class.course}}</span><br>
<span>{{class.school}}, {{class.semester}}</span>

{% endfor %} -->