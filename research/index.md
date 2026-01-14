---
title: Research
nav:
  order: 1
  tooltip: High-level research overview
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

Research is most fruitful (and most fun) at the intersection of different fields of research. At the core of our research is the development of methods that
provide *explanations* for complex machine learning models, as well as the development of *inherently interpretable* machine learning models.
We are particularly interested in getting a better understanding of how information is encoded and propagated *inside* a neural network, nowadays coined *mechanistic interpretability*, or to inform *inherently interpretable* and *neuro-symbolic*
architecture designs.
Our research spans from foundations to applications in practice. One focus lies on *extracting new scientific insights* from models that often surpass human experts through methods for Interpretability of Machine Learning models.
In molecular biology we for example use explanations of models to get new knowledge about the complex genomic mechanisms driving cancer or aging.

{% include section.html %}

{% capture text %}
*Inherently interpretable models* are key to ensure explanations that are *faithful* to the actual model decisions. Such Explanations that reveal the true decision-making of the model are key in high-stakes settings in practice,
for example in biomedical imaging -- e.g., predicting cancer risk or events based on radiological images, tissue stains, or skin screens.
We are interested in developing new methodology that yields both highly performant but still inherently interpretable models, ensure that explanations are correctly grounded in the input image, as well as models that are inherently interpretabl while emitting other properties such as OOD robustness.
Most recently, we have been interested in enabling inherent explanations on downstream tasks for foundation models such as CLIP, and making multimodal model reasoning, such as of Vision Language Models, more transparent.

{% endcapture %}

{%
  include feature.html
  image="images/cave.png"
  title="Inherently Interpretable decision-making"
  text=text
%}

{% include section.html %}

{% capture text %}

*Post-hoc* explainability methods aim to provide explanations of what an already trained model, usually a neural network, learned and how it uses this information to arrive at a prediction.
While not making a black box model fully transparent, by providing a glimpse into the black box these methods have the great advantage that they do not compromise performance, which is a desiderata for a neural network in practice. 
A majority of post-hoc explanation approaches, however, focus on *instance-specific explanations*, giving insights into why a decision was made for a particular instance (e.g., saliency maps, GradCam, Integrated Gradients,
LIME, ...).
We are interested in *faithful explanations* that accuratly describe the general information encoded for example by a group of neurons and discovering such feature-encoding sub-networks (*mechanistic circuits*).
A recent focus of the group has been to also develop *theoretical guarantees*, e.g. on robustness or uncertainty, for such circuitry

{% endcapture %}

{%
  include feature.html
  image="images/explainn.png"
  title="Global Explanations"
  text=text
%}



{% include section.html %}

{% capture text %}

*Neuro-symbolic approaches* to machine learning promise full interpretability through *symbolic encodings* in a neural network that can be parsed and understood by a human domain expert. While highly interesting, these approaches remain largely theoretical, as such architectures are hard to define and even harder to optimize. We focus on recent advances for *binarized and ternarized neural network architectures* from different fields, such as ML for embedded devices, and how we can transfer these to neuro-symbolic learning. In several biological applications as well as settings with transactional data, such architectures already provide a fully interpretable approach that allows to derive new insights directly from the network.

{% endcapture %}

{%
  include feature.html
  image="images/binaps.png"
  title="Neuro-symbolic architectures"
  text=text
%}


{% include section.html %}

{% capture text %}

*Sparse neural networks* not only provide more resource-efficient alternatives to their dense counterparts at same performance, captured by the *Lottery Ticket Hypothesis*, but also represent useful information in their network topology compared to the standard fully connected layers in dense networks.
We focus on the question of how we can prune networks to *extreme sparsity*, and how such sparse neural networks can then yield more explainable decision-making.

{% endcapture %}

{%
  include feature.html
  image="images/pruning.png"
  title="Sparse Neural Networks"
  text=text
%}

{% include section.html %}


