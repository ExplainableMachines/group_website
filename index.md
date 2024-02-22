---
---

# Explainable Machine Learning Group Homepage

This is the home of the Explainable Machine Learning research group of the Department for Computer Vision and Machine Learning of the Max Planck Institute for Informatics. Here, we provide an overview as well as all the details on our ongoing and past work around Explainability in Machine Learning, including generation of explanations for black box models, inherently interpretable neural network approaches, and their applications.

{% include section.html %}

## News

{% capture news1 %}
 1/1/24 *The Explainable Machine Learning Group was founded.*
{% endcapture %}

{%
  include alert.html
  type="info"
  content=news1
%}


{% include section.html %}

## Highlights

{% capture text %}

Interested in Explainability of Machine Learning models? See at a glance!

{%
  include button.html
  link="research"
  text="Overview"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="https://imgs.xkcd.com/comics/machine_learning.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

We are interested in all facets of Explainability in Machine Learning and beyond.
Get more information on individual projects from our group.

{%
  include button.html
  link="projects"
  text="Browse"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="https://imgs.xkcd.com/comics/dependency.png"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Great research happens in a great environment.
Meet our diverse team that makes this possible!

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="https://imgs.xkcd.com/comics/i_in_team.png"
  link="team"
  title="Our Team"
  text=text
%}
