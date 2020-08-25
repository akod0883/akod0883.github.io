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
* B.S. in University of Illinois Urbana-Champaign, 2023

Work experience
======
* Summer 2020: Research Assistant
  * University of Chicago
  * Duties included:
  * One of thirty accepted into program with 310 applicants.
  * Created a Microk8 Kubernetes deployment for launching multiple instances of a virtual environment designed for testing and creating machine learning algorithms on edge devises.
  * Streamlined the creation of an Openstack image for gpu-based, arm64 and compute-hastwell hardware  using GitHub Actions
  * Created python script that backdates images on the Openstack cloud, so users know the most up-to-date image.


* Summer 2019: Research Assistant
  * Argonne National Laboratories
  * Duties included:
  * Helped create a python script that can create a Deep Learning dataset for classifying car make and model from videos of cars driving with high accuracy using various python libraries.
  * Coauthored and presented paper at PAISE 2020 Parallel AI and Systems for the Edge as apart of IPDPS
  * Performed error tests Docker containers, Odriod, and Arduino hardware.

* Summer 2017: Research Assistant
  * Argonne National Laboratories
  * Participated in the Multiple Myeloma Dream Challenge and helped develop a Machine Learning algorithm to improve patient stratifications to optimize treatment and develop new therapies for high risk patients with Multiple Myeloma
  * I compared file transfer speeds onto the Wasabi and Amazon S3 cloud using Boto3 and Globus API and found that files transfer 15% faster onto Wasabi’s cloud

Skills
======
* Python
* C
* Java
* Bash
* C++
* LC3
* Markdown
* YAML

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
