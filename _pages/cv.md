---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Industrial Ph.D. in applied mathematics, École des Ponts, IP Paris, Sep 2022 - Sep 2025
* Master2 in applied mathematics (MODO), Université Paris Dauphine-PSL, Paris, Oct 2020 – Sep 2021
* Engineering Degree in Computer Science, Ecole Nationale Supérieure d’Informatique, Algiers, Sep 2015 – Jul 2020

Work experience
======
* Optimization Scientist, Persee, Dec 2021 – Current

* Data Scientist Intern, Groupement Les Mousquetaires, Mar 2021 - Sep 2021

* Data Scientist Intern, Optimum Telecom Algérie, Algiers, Oct 2019 - July 2020
  
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
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
