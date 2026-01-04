---
title: "b-marker Blog"
date: 2026-01-04 11:17:00 +0800
categories: [Home]
tags: [Intro]
---

<!-- Load b-marker-dev Logo -->

<img src="https://github.com/b-marker-dev.png" width="100" height="100" alt="Gary Chiu" style="border-radius: 50%;">
<h3>Gary Chiu (dev@b-marker.com)</h3>

<!-- Force README Markdown -->
{% capture readme_content %}{% include_relative README.md %}{% endcapture %}
{{ readme_content | markdownify }}
