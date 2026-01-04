---
title: "b-marker Blog"
date: 2026-01-04 11:17:00 +0800
categories: [Home]
tags: [Intro]
---

{% capture readme_content %}{% include_relative README.md %}{% endcapture %}
{{ readme_content | markdownify }}
