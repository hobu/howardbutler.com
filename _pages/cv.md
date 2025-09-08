---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


Work experience
======
* 2001 – current : President – [Hobu, Inc](https://hobu.co)
  * Hobu, Inc. is an open source software consultancy focused on LiDAR, point
    clouds, and geospatial software. It has led the creation of [PDAL](https://pdal.org),
    [COPC](https://copc.io), [Entwine](https://entwine.io), and [SilviMetric](https://silvimetric.com)
    open source LiDAR software tools.

* 2001 – 2007: Systems Analyst I, II, & III – Iowa State University
  * GIS software engineering, analysis, and design

* 1998 – 2001: Graduate Research Assistant – Iowa State University


Open Source Leadership
======

  <ul>{% for post in site.opensource reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* C, C++, Python
* [AWS](https://aws.amazon.com/), [Azure](https://azure.microsoft.com/en-us/), [GCS](https://cloud.google.com/)
* LiDAR data management, compression, and exploitation
* Open source software engineering, project management, and maintenance


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Education
======
* M.S. Interdisciplinary Graduate Studies, Iowa State University, 2001
* B.S. Agricultural Systems Technology, Iowa State University, 1998


