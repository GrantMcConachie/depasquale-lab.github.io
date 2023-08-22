---
title: What we do
nav:
  order: 1
  tooltip: Research
---

# <i class="fas fa-microscope"></i>Research

For a full list of publications, see [Brian's Google Scholar](https://scholar.google.com/citations?user=dkRSv1AAAAAJ&hl=en).
{:.center}

{% include section.html %}

{% capture text %}
Biological neural networks compute quite differently than artificial neural networks used in machine learning. For example, although real neurons communicate with spikes, reproducing this feature in artificial models has been a challenge. We develop methods for training recurrent neural networks (RNNs) of spiking model neurons and use it to construct spiking networks capable of performing tasks previously beyond our reach. My method established a key conceptual link between spiking networks and more commonly used ‘rate’ networks that illustrated how spiking networks can be constructed to perform virtually any task modeled with rate networks. Additionally, I used my approach to understand the mechanistic origin of latent factors (e.g., principal components), a burgeoning statistical framework for describing neural population activity. I constructed spiking RNNs that produced latent factors derived from neural recordings in the primary motor cortex, and illustrated how the factors are constructed within the network’s synaptic connectivity. A second challenge for real and artificial neural circuits is performing tasks with long temporal dependencies. I invented a novel network training method called full-FORCE that can build networks able to perform tasks over behaviorally relevant timescales. full-FORCE has largely supplanted its widely-used predecessor, ‘FORCE’, as the premier, non-gradient-based method for training RNNs, and multiple groups have used it to address their own unique research questions.

[**Key paper**: The centrality of population-level factors to network computation is demonstrated by a versatile approach for training spiking networks](https://doi.org/10.1016/j.neuron.2022.12.007)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="https://ars.els-cdn.com/content/image/1-s2.0-S0896627322010807-gr1_lrg.jpg"
  headline="Methods for constructing biophysically detailed and data-constrained artificial neural networks"
  text=text
%}

{% include section.html %}

{% capture text %}
As a postdoctoral researcher, I shifted focus to statistical models of neural dynamics underlying decision-making. I developed comprehensive statistical models for characterizing the unobserved (‘latent’) temporal processes reflected in neural activity that underlie decisions. These models reflect a substantive improvement over prior approaches; whereas prior methods tended to either analyze neurons individually or the behavioral output of an animal in isolation, my method jointly modeled behavior and multi-neuronal responses simultaneously, thereby providing a comprehensive and statistically rigorous model of decision-making. I applied these methods to characterize the unique accumulation ‘strategy’ employed by multiple cortical and subcortical brain regions in rats performing pulsed-based evidence accumulation tasks, and found that different brain regions contributed to the overall accumulation process that drove behavior in radically different ways. The generality of my method allowed me to apply it to behavioral data collected from non-human primates and humans performing a similar task, and to extend the framework to consider how the history of animal choices in a trial-based decision-making task impacts the underlying temporal processes that determine future decisions. 

[**Key paper**: Neural population dynamics underlying evidence accumulation in multiple rat brain regions](https://www.biorxiv.org/content/10.1101/2021.10.28.465122v1)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/image0.jpeg"
  headline="Latent dynamical analysis of behavior and neural activity during sensory decision-making"
  text=text
%}