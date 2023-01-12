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

## Instructor

{% assign instructors = site.staffers | sort: 'index' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Overview of the course

- Week 1: Introduction to R 
- Week 2: Data visualization with **ggplot2**
- Week 3: Data transformation with **dplyr**
- Week 4: Statistical modeling and testing

## Course Logistics

- **Time**: Tue, Thu 12:00-1:20pm
- **Dates**: January 17, 19, 24, 26, 31, February 2, 7, 9.
- **Location**: In-person at STLC 115
- **Links**:
    - [Canvas](https://canvas.stanford.edu/courses/164301): The course Canvas page
      contains links and resources only accessible to students.
    - [Gradescope](https://www.gradescope.com/courses/486004): We use Gradescope for managing coursework (turning in, returning grades).  
- **Course Grade**: The course grade (Satisfactory/No Credit) will be based on:
    - 3 Homework assignments (30%)
    - Final project proposal (10%)
    - Final project report (60%)

## Textbook
There are no required textbooks for this course. However, [R for Data Science](http://r4ds.had.co.nz/) by Hadley Wickham and Garrett Grolemund (O’Reilly Media, 2017, available for free online) is recommended as an aid to understanding the course material. Some of the course material is based on this book.

## Students with Documented Disabilities
Students who may need an academic accommodation based on the impact of a disability must initiate the request with the Office of Accessible Education (OAE). Professional staff will evaluate the request, review appropriate medical documentation, recommend reasonable accommodations, and prepare an Accommodation Letter for faculty. The letter will indicate how long it is to be in effect. Students should contact the OAE as soon as possible since timely notice is needed to coordinate accommodations. Students should also send your accommodation letter to instructors as soon as possible. The OAE is located at 563 Salvatierra Walk (phone: 723-1066, URL: http://oae.stanford.edu).

## Honor Code
Students should be familiar with and act in accordance with the [honor code](https://communitystandards.stanford.edu/policies-guidance/honor-code).