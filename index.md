---
layout: default
title: Home
seo:
  type: Course
  name: {{ site.title }}
nav_order: 1
---

# {{ site.tagline }}

<!--{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}-->

This short course runs for weeks one through four of the quarter. It is recommended for students who want to use R in statistics, science or engineering courses, and for students who want to learn the basics of data science with R. The goal of the short course is to familiarize students with some of the most important R tools for data analysis. Lectures will focus on learning by example and assignments will be application-driven. No prior programming experience is assumed. 

## Overview of the course:

- Week 1: Introduction to R 
- Week 2: Data visualization with **ggplot2**
- Week 3: Data transformation with **dplyr**
- Week 4: Statistical modeling and testing

## Instructor

{% assign instructors = site.staffers | sort: 'index' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Course Logistics
&nbsp;

**When**: Class is Tuesdays and Thursdays 12:00-1:20pm.

**Where**: Class will be in person at STLC 115.

**Links**:
- [Canvas](): The course Canvas page
  contains links and resources only accessible to students.
- [Gradescope](): We use Gradescope for managing coursework (turning in, returning grades).  

**Course Grade**: The course grade (Satisfactory/No Credit) will be based on the following components.

- 3 Homework assignments (40%)
- Final project proposal (10%)
- Final project report (50%)
