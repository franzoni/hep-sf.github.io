---
title: "CERN in GSoC"
author: "Benedikt Hegner"
layout: default
---
# Project Proposals at CERN

## Project Proposals

{:.table .table-hover .table-striped}
{% for page in site.gsocproposals %}{% if page.organization == "CERN" %} | [ {{ page.title }} ]( {{ page.url }} ) | {% endif %}
{% endfor %}