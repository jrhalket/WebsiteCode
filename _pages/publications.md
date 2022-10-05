---
layout: page
permalink: /publications/
title: Publications
description:
years: [2020, 2018, 2015, 2014, 2006, 2005, 2004, 2002]
nav: true
nav_order: 1

---
<style>
.publications{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>
## Working papers
<div class="publications">
{% bibliography -f papers -q @unpublished %}
</div>

## Refereed journal articles
<div class="publications">
{% bibliography -f papers -q @article %}
</div>

## Technical reports
<div class="publications">
{% bibliography -f papers -q @techreport %}
</div>

## Older, sleeping papers
<div class="publications">
{% bibliography -f papers -q @phdthesis,@report %}
</div>
