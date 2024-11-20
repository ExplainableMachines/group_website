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
{% include list.html data="members" component="portrait" filters="role: ril" %}
{% include list.html data="members" component="portrait" filters="role: master" %}
{% include list.html data="members" component="portrait" filters="role: hiwi" %}




# {% include icon.html icon="fa-solid fa-users" %}Alumni


{% include list.html data="members" component="portrait" filters="role: alumni" %}