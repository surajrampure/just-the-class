---
layout: page
title: Calendar
nav_order: 2
description: The weekly event schedule.
---

# Calendar

**TODO**: We can either edit this, or use Google calendar. Either works.

<!-- Schedule data are defined as YAML [data files](https://jekyllrb.com/docs/datafiles/) following the example format in `_data/schedule`.

Multiple schedules can be rendered on a page, each with their own events and hour range. -->

## Weekly Schedule

{% include schedule.html data=site.data.schedule.weekly interval=30 row_height=40 %}

## Office Hours Schedule

{% include schedule.html data=site.data.schedule.office-hours interval=30 row_height=40 %}
