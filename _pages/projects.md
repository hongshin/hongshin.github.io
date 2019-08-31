---
layout: page
title: Projects
permalink: /projects/
<!-- description: A growing collection of your cool projects. -->
---

#### Government Research Grants ####
1. Developing Automated Software Test Generation Techniques Using Data-driven Analyses, Young Researcher Program Funded by NRF, 2017-current
1. Intelligent Automation Techniques for Fullstack Software Debugging, Next-Generation Information Computing Development Program Funded  by NRF, 2017-current
1. Detecting Software Performance Bugs Using Automated Unit Test Generation Techniques, Young Researcher Program Funded by NRF ,2015-2016

#### Industry Collaborations ####
1. Asessing Quality of Unit Test Cases Automatically, Samsung Research, 2019
1. Detecting Multithreaded Program Errors in Real-time Operating Systems, Samsung Memory Research Institute, 2017-2018
1. Machine Learning Approach to Analyze Static Analysis Alerts, Samsung Research, 2017

<!--
{% for project in site.projects %}

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
