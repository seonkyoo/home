---
layout: page
title: Research
permalink: /research/
description: 
---

My research centers on the interface between physical and data sciences, aiming at improving fundamental understanding and characterizing uncertainty of flow, transport, and reaction in hydrological systems. The schematic figure below shows two directions of my research: forward problems and inverse problems.
<div class="img_row">
    <img class="col three" src="{{ site.baseurl }}/assets/img/forward_inverse.jpg">
</div>

I combine theoretical and computational approaches such as fluid dynamics, extreme value theory, Bayesian analysis, fractals, stochastic modeling, deep learning, and computational fluid mechanics. 


My specific research topics include:
<ul>
    <li>groundwater flow</li>
    <li>non-Fickian mass transport in hydrogeologic systems</li>
    <li>mixing and reaction</li>
    <li>data assimilation</li>
    <li>physics-informed machine learning</li>
    <li>risk assessment</li>
</ul>


<hr>

<!-- I currently study anomalous transport and mixing-induced reaction in rough fractures.  -->

<!-- {% for project in site.projects %}

{% if project.redirect %}
<div class="project">
    <div class="thumbnail">
        <a href="{{ project.redirect }}" target="_blank">
        {% if project.img %}
        <img class="thumbnail" src="{{ project.img | prepend: site.baseurl | prepend: site.url }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ project.title }}</h1>
            <br/>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>
{% else %}

<div class="project ">
    <div class="thumbnail">
        <a href="{{ project.url | prepend: site.baseurl | prepend: site.url }}">
        {% if project.img %}
        <img class="thumbnail" src="{{ project.img | prepend: site.baseurl | prepend: site.url }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ project.title }}</h1>
            <br/>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>

{% endif %}

{% endfor %}
 -->