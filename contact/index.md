---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

If you have questions about our work or want to discuss research, please reach out!
If you have a strong background in Explainable Machine Learning and find a suitable role below, please reach out with your CV, an up-to-date transcript of your studies, and a brief introduction of who you are and what your research interests are.

{%
  include button.html
  type="email"
  text="E-Mail"
  link="jonas.fischer@mpi-inf.mpg.de"
%}

{%
  include button.html
  type="address"
  tooltip="Location of the Max Planck Institute for Informatics"
  link="https://www.mpi-inf.mpg.de/institute/address"
%}


{% include section.html dark=true %}

{% capture col1 %}
### PhD openings

If you are interested in joining an international and diverse environment in
one of the most renowned Computer Science institutes in the world
and have a track record of academic achievments in a related field,
please reach out!
{% endcapture %}

{% capture col2 %}
### Master thesis

For interested Master students with background in Machine Learning (good transcript of records
of advanced ML lectures required), we have
exciting research topics for a thesis related to Explainable ML. If you want to
do research at the cutting edge, reach out!
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
