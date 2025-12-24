---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

 {% if site.author.googlescholar %}
   You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.
 {% endif %}

The list below is automatically generated from my Google Scholar profile (as of December 24th, 2025) using [google-scholar-for-github-pages](https://github.com/cmccomb/google-scholar-for-github-pages).

### Submitted Preprints
{% include publications link=true venue_search="rxiv" %}

### Published Articles
{% include publications link=true venue_exclude="bioRxiv;PsyArXiv;arXiv" venue_search_exclude="rxiv;Rxiv;arXiv" %}