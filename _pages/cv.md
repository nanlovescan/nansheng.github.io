---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Research interest
=====
* Systems
  * Areas: Storage and File systems, Operating Systems, Distributed Systems, Database systems
  * Focus: Non-Volatil Memory (NVM), Persistent Memory (PM) aware system design
    * Key-value store and its core indexing structures
    * Improving the performance and reliability of NVM-based file systems

Education
======
* B.S. in South Korea, Hongik University, 2015
* M.S. in South Korea, UNIST (Ulsan National Institute of Science & Technology), 2018
* Ph.D in United States of America, University of Texas at Austin, 2018 (Starting from Fall 2018)

Work experience
======
* 03.2018~07.2018: Researcher
  * UNIST (Ulsan National Institute of Science & Technology)
  * Duties included: I participated in the projects in order to propose the compiler-directed solution on NVM-based systems.

* 06.2017~09.2017: Research Associate Intern
  * Hewlett Packard Enterprise
  * Duties included: Working in key-value store (KVS) group with Kimberly Keeton, Haris Volos, and Yupu Zhang, I attended a DRAM cache project for NVM-aware KVS working on Fabric-attached memory.
  * Supervisor: Kimberly Keeton

* 10.2015~02.2016: Researcher
  * UNIST (Ulsan National Institute of Science & Technology)
  * Duties included: Working in NECSST lab under Prof. Sam H. Noh, I analyed NVM-based file system (PMFS) and evaluated the performance of it.
  * Supervisor: Sam H. Noh
  
Skills
======
* Languages
  * C, C++, Python, x86 assembly, Bash script
* System programming
  * Linux kernel, Memcached, Tizen
* Benchmarks
  * Filebench, Fio, YCSB, ForestDB-benchmark, MC-benchmark, SPLASH3, Parsec, SPEC SFS2014

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
