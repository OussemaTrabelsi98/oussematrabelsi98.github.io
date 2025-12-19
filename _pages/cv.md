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
* Ph.D. in Urban Planning, McGill University, Montréal, QC, 2028 (expected)  
  * Supervisor: [David Wachsmuth](https://www.mcgill.ca/urbanplanning/david-wachsmuth)
  
* M.Sc. in Urban Studies, Montréal, QC, 2022–2024  
  * Primary supervisor: [Nick Revington](https://inrs.ca/en/research/professors/nick-revington/)  
  * Co-supervisor: [Cédric Brunelle](https://inrs.ca/la-recherche/professeurs/cedric-brunelle/)

* B.B.A. (Bachelor of Business Administration), Institut Supérieur des Études Technologiques, Sfax, Tunisia, 2017–2020

Work experience
======

* Mar 2025 – Present: Data Lead, Curbcut, Montréal, QC  
  * Structured housing databases and automated data pipelines for integration into multiple platforms (including Curbcut), with complete documentation for transparency, traceability, and maintainability  
  * Managed the full data lifecycle from raw ingestion to analytics/visualization outputs, documenting sources, transformations, and update frequencies  
  * Translated end-user needs (including public-sector decision makers) into data structures and presentation formats aligned with real use cases  
  * Collaborated with technical and research teams to continuously improve platforms through use-case experimentation and data-architecture optimization  

* Mar 2024 – Feb 2025: Research Officer, City of Montréal, Montréal, QC  
  * Updated the data and methodology of the Living Environment Equity Index  
  * Produced interactive, universally accessible borough-level reports across five themes (poverty, children, youth, older adults, activity limitations) using R Markdown  
  * Conducted in-depth analyses aligned with service priorities and Montréal social issues through an intersectional (GBA+/ADS+) lens for internal programs  
  * Developed Python workflows to automate data extraction from PDFs/images and generate standardized result tables and reports  

* Apr 2023 – Present: Research Assistant, Université Laval, Montréal, QC  
  * Structured municipal-level census data for Québec (1981–2021)  
  * Built a database of major public investments (highways, hospitals, schools, etc.), 1971–2021  
  * Developed a growth-model framework to estimate the impacts of public investments on Québec’s economic development  

* Apr 2023 – Apr 2024: Research Assistant, Université du Québec à Montréal (UQAM), Montréal, QC  
  * Conducted a literature review on gentrification and urban transformations  
  * Structured and cleaned large longitudinal datasets on business dynamics in U.S. cities  
  * Produced reports using descriptive statistics and causal regression models to assess how business movements shape urban dynamics  

* 2022 – 2024: Research Assistant, INRS – Spatial Statistics and Urban Development Lab, Montréal, QC  
  * **ARTM project:** Structured and cleaned multi-period census data for longitudinal analysis; developed a spatial interpolation method to adapt census data to transportation planning zones; designed and implemented spatial panel regression models to analyze employment with spatial and temporal dimensions  
  * **Teaching support:** Migrated a GIS course from ArcMap to ArcGIS Pro, including updates to datasets and teaching materials  

  
Skills
======

* Data engineering & reproducible pipelines
  * Automated ETL workflows; structured data products; versioned documentation for transparency and maintenance

* Statistical analysis & causal inference
  * Panel models; difference-in-differences and event-study designs; regression-based causal analysis

* Spatial data science (GIS)
  * Spatial interpolation; spatial weights / spillovers; census-tract and municipal geographies; ArcGIS Pro workflow

* Programming & tools
  * R (tidyverse, R Markdown), Python (automation scripts), Git/GitHub

* Data communication
  * Interactive, accessible reporting; stakeholder-oriented outputs for public-sector users


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks and presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Ongoing research projects
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
