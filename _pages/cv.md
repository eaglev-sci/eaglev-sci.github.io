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
* Master of Science and Engineering, Biotechnology specialty, Mines Paris - PSL, Paris, 2018
* Preparatory Classes, Specialization in Physics & Chemistry, Lycee Cemenceau, Nantes, 2012-2014

Work experience
======
* April 2019 - March 2022: Research Engineer, Institut Curie (LSMP) Paris, France
  * Mass Spectrometry Proteomics
  * Provided support to collaborators of the facility to analyse, visualize and interpret their proteomics data
  * Maintained and improved myProMS, software for proteomics data analysis
  * Implemented new functionalities to the software (Hydrophobicity of peptides, Absolute Quantification, GSEA, Quality Control)
  * Managers: Dr. Damarys Loew, Dr. Patrick Poullet

* April - August 2018: Research Intern, European Bioinformatics Institute, Cambridge, UK
  * Computational biology of proteins and ageing
  * Studied protein-ligand interactions through structural aspects
  * Evaluated chemical compounds thought to affect human ageing, and their target proteins
  * Built an informatic pipeline in Python / Bash, selecting the best compounds to test in Drosophila melanogaster
  * Integrated bioinformatic tools such as Docking softwares (GOLD, Vina) and Comparative Modelling programs (MODELLER)
  * Supervisor: Pr. Dame Janet Thornton

* March - Aug 2017: Research Intern, Centre for Molecular Medicine Norway (NCMM) Oslo, Norway
  * Computational biology & Gene regulation
  * Modelled Transcription Factor-DNA binding at methylated sites
  * Used whole-genome methylation data and expanded DNA alphabet with machine learning algorithm to predict TF-DNA binding for Arabidopsis thaliana model organism
  * Supervisor: Dr. Anthony Mathelier

<!--
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3
-->

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<!--  
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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
-->