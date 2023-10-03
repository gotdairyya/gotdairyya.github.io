---
layout: default
title: c.v.
---

<!--
pdf version [here](/assets/images/Akbaba-CV.pdf) -->

### peer-reviewed conference publications

{% include cv_publications.html data=site.data.publications %}
<br>

### peer-reviewed abstracts + short papers

{% include cv_publications.html data=site.data.shortpubs %}
<br>

### non-academic publications

check out my [substack](https://gotdairyya.substack.com/) for more opinion-y pieces

{% include cv_publications.html data=site.data.otherpubs %}
<br>

### invited talks

{% include cv_publications.html data=site.data.talks %}

<br>

### invited workshops

{% include cv_publications.html data=site.data.workshops %}

<br>

### service

{% include cv_publications.html data=site.data.service %}

<br>

### reviewing

{% include cv_publications.html data=site.data.reviewing %}

<br>

### teaching

{% assign teaching = site.data.teaching | sort: "year" %}
{% for class in teaching reversed %}
<bold>{{class.role}}</bold>
<span>{{class.course}}</span><br>
<span>{{class.school}}, {{class.year}}</span>

{% endfor %}

<br>

<!-- ## outreach

I find it important to find different ways to share research outside of academia.
So far I give myself a 2/5 at my attempts.

|          |     |                                                                                                                              |
| -------- | --- | ---------------------------------------------------------------------------------------------------------------------------- |
| **2022** |     | [**SHETech Explorer Day**](https://shetechexplorer.com/)                                                                     |
|          |     | [Data Portraits](https://observablehq.com/@gotdairyya/data-portraits-for-shetech) for young girls to consider future in STEM |
|          |     |                                                                                                                              |
| **2020** |     | [**VDL Blog**](https://vdl.sci.utah.edu/blog/)                                                                               |
|          |     | Started blog to make research papers more accessible.                                                                        | -->
