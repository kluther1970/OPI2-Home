---
title: The Team
layout: sidebar-page
position: 1
---

{% assign staff = site.people | where: "agency", "oci" | sort: "start_date"  %}
{% include page-section--people-team.html
  section_headline=page.staff_section_headline
  people=staff %}
