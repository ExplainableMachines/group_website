---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team


{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: visitingres" %}
{% include list.html data="members" component="portrait" filters="role: ril" %}
{% include list.html data="members" component="portrait" filters="role: master" %}
{% include list.html data="members" component="portrait" filters="role: bachelor" %}
{% include list.html data="members" component="portrait" filters="role: hiwi" %}


{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}Alumni


{% include section.html %}


{% include list.html data="members" component="portrait" filters="role: alumni" %}