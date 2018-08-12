---
layout: archive
title: "Curriculum Vitae [(CV)](http://sekwonlee.github.io/files/cv.pdf)"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[<span style="color:blue">[Downloadable CV]</span>](https://sekwonlee.github.io/files/cv.pdf)

Research interest
=====
* <b>Systems</b>
  * <b>Areas:</b> Storage and File systems, Operating Systems, Distributed Systems, Database systems
  * <b>Focus:</b> Non-Volatil Memory (NVM), Persistent Memory (PM) aware system design
      * Key-value store and its core indexing structures
      * Improving the performance and reliability of NVM-based file systems

Education
======
* <b>Ph.D in United States of America, The University of Texas at Austin, Fall 2018 ~ Present</b>
* <b>M.S. in South Korea, UNIST (Ulsan National Institute of Science & Technology), 2018 </b>
  * <b>Advisor</b>: Prof. Sam H. Noh
* <b>B.S. in South Korea, Hongik University, 2015</b>

Work experience
======
* <b>Researcher</b>, 03.2018~07.2018
  * UNIST (Ulsan National Institute of Science & Technology)
  * Duties included: Working for a project that proposes the compiler-directed solution on NVM-based systems.

* <b>Research Associate Intern</b>, 06.2017~09.2017
  * Hewlett Packard Enterprise
  * Duties included: Working in key-value store (KVS) group with Kimberly Keeton, Haris Volos, and Yupu Zhang, I attended a DRAM cache project for NVM-aware KVS working on Fabric-attached memory.
  * Supervisor: Kimberly Keeton

* <b>Researcher</b>, 10.2015~02.2016
  * UNIST (Ulsan National Institute of Science & Technology)
  * Duties included: Working in NECSST lab under Prof. Sam H. Noh, I analyed NVM-based file system (PMFS) and evaluated the performance of it.
  * Supervisor: Sam H. Noh
  
Skills
======
* <b>Languages</b>
  * C, C++, Python, x86 assembly, Bash script
* <b>System programming</b>
  * Linux kernel, Memcached, Tizen
* <b>Benchmarks</b>
  * Filebench, Fio, YCSB, ForestDB-benchmark, MC-benchmark, SPLASH3, Parsec, SPEC SFS2014

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
 
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
