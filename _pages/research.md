---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

The research for my Ph.D. deals with understanding the effects of long, persistent drought on hydrological systems and on the reliability of conceptual hydrological models.
Specifically, I am focussing on the Millennium drought, which affected an area in excess of 1 million km<sup>2</sup> in south-eastern Australia between ca. 1997 and 2009.
I approach research projects in a multidisciplinary and data-driven way, with the support of digital tools for data analysis, modelling and visualization.
For most of my research, I am using hydrometeorological data from 155 catchments affected by the Millennium drought in the Australian state of Victoria.

Currently my Ph.D. project is developing in two main directions:
The first deals with hydrological modelling and focuses on understanding how the Millennium drought affected the reliability of streamflow projections in Victoria, this included a small study on the effects of the choice of calibration sequence on model performance during drought. The second stream deals with understanding hydrological processes during drought and for this I am currently focussing on storage dynamics; the aim is to assess how storage capacity changed during the drought and whether this affected the behaviour of hydrological catchments during this period.

Eventually, I am planning to bring these two pieces together in the final part of my Ph.D. project, where I will try to improve the reliability of hydrological models during long, dry periods such as the Millennium drought.


{% include base_path %}
{% assign ordered_pages = site.research | sort:"order_number" %}
{% for post in ordered_pages %} {% include archive-single.html type="grid" %} {% endfor %}
