---
---

# Explainable Machine Learning Group Homepage

This is the home of the Explainable Machine Learning research group of the Department for Computer Vision and Machine Learning of the Max Planck Institute for Informatics. Here, we provide an overview as well as all the details on our ongoing and past work around Explainability in Machine Learning, including generation of explanations for black box models, inherently interpretable neural network approaches, and their applications.

{% include section.html %}

## News

{% capture news9 %}
 10/25 I am happy to announce that this semester we are offering a seminar on [*Explainable Machine Learning*](https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/teaching/courses-1/ws-2025-26-explainable-machine-learning-exml-seminar) and [*Machine Learning Approaches for Building Virtual Cell Models*](https://cms.sic.saarland/bi_mla_25/) in collaboration with other groups at Saarland University.
{% endcapture %}

{% capture news8 %}
 10/25 Excited to share the acceptance of *FaCT* at NeurIPS, which equips neural networks with concept traces explaining the underlying decision-making faithful to the true network reasoning, led by associated PhD student Amin.
{% endcapture %}

{% capture news7 %}
 7/25 Happy to share the acceptance of *VITAL* at ICCV, which enables more realistic feature visualizations to understand neural network decision making, led by our PhD student Ada, and *Spotlight* at ACL, which supports users in identifying the effects of prompt and model changes led by the group of Michael Hedderich at LMU.
{% endcapture %}

{% capture news6 %}
 1/10/25 PHOENIX was highlighted as one of the "[Advances in Cancer Biology Research](https://www.cancer.gov/about-nci/organization/dcb/progress/cancer-biology-advances)" in 2024 by the NCI (the National Cancer Institute of the US)!
{% endcapture %}

{% capture news5 %}
 11/28/24 Jonas gave an invited talk on *Mechanistic Interpretability of Neural Networks* at an XAI Symposium in Mainz (organized within the hessian.AI – Connectom network funding program).
{% endcapture %}

{% capture news4 %}
 10/6/24 [DASH](https://github.com/QuackenbushLab/DASH) was accepted at NeurIPS 2024! Vancouver, here we come.
{% endcapture %}

{% capture news3 %}
 6/27/24 [Ada](https://explainablemachines.github.io/group_website/members/ada-goerguen.html) joins the team as the very first PhD student. Welcome!
{% endcapture %}

{% capture news2 %}
 6/10/24 Our lab got an OpenAI grant for API credits as part of the [OpenAI Researcher Access program](https://openai.com/form/researcher-access-program/).
{% endcapture %}

{% capture news1 %}
 1/1/24 *The Explainable Machine Learning Group was founded.*
{% endcapture %}

{%
  include alert.html
  type="info"
  content=news7
%}

{%
  include alert.html
  type="success"
  content=news6
%}

{%
  include alert.html
  type="info"
  content=news5
%}

{%
  include alert.html
  type="info"
  content=news4
%}

{%
  include alert.html
  type="info"
  content=news3
%}

{%
  include alert.html
  type="success"
  content=news2
%}

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
  link="https://imgs.xkcd.com/comics/machine_learning.png"
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
  link="https://imgs.xkcd.com/comics/dependency.png"
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
  link="https://imgs.xkcd.com/comics/i_in_team.png"
  title="Our Team"
  text=text
%}
