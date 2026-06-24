---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research spans two interconnected areas at the intersection of thermal science, human physiology, and engineering.

The first area focuses on **human thermoregulation and heat stress**. I develop and refine computational models that simulate heat and mass transfer from the human body under extreme thermal environments — both hot and cold. This work includes advancing thermoregulatory models that account for individual variability in body type, metabolic rate, and physiological response. A current NSF-funded project ([Award #2152468](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2152468)) uses advanced mobile biometeorological stations and thermal manikins to measure realistic heat exposure in field conditions, with a focus on mitigating health risks from extreme heat across diverse populations.

The second area investigates the **role of clothing and personal protective equipment in heat transfer**. I study how garments, gloves, and wearable devices (including exosuits) affect the thermal microclimate at the skin surface, using thermal manikins, 3D scanning methods, and computational simulation. This research has direct applications in occupational safety, athletic performance, and military/first-responder gear design.

&nbsp;

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
