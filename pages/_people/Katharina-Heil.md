---
title: "Katharina Heil"
layout: default
excerpt_link: 'https://elixir-europe.org/about-us/who-we-are/hub'
excerpt_separator: <!--more-->
category:
  - contact
  - people
tags:
  - contacts
  - people
  - IS_2021_Data
  - IS_2021_Exchange
---

<h2>{{page.title}}
{%- assign portrait = page.title | replace: ' ', '-' -%}
{%- for static_file in site.static_files -%}
    {%- if static_file.extname == '.jpg' or static_file.extname == '.png'  -%}
        {%- assign imgf = static_file.basename | replace: ' ', '-' -%}
        {%- if imgf == portrait -%}
<img style="float: right; width: 80px; margin-top: -12px; margin-right: 10px; margin-bottom: -50px;" src="{{ static_file.path | relative_url}}" />
        {%- endif -%}
    {%- endif -%}
{%- endfor -%}</h2>

* ELIXIR Communities Coordinator 

<!--more-->

email [katharina.heil@elixir-europe.org](mailto:katharina.heil@elixir-europe.org)  
