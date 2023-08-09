---
title: Research
nav:
  order: 1
  tooltip: Published works
---

For a full list of publications, see [Google Scholar](https://scholar.google.com/citations?user=dkRSv1AAAAAJ&hl=en).
{:.center}

{% capture text %}
 My PhD research focused on the development of novel methods for training artificial neural networks bound by the constraints of real neural systems. For example, although real neurons communicate with spikes, reproducing this feature in artificial models has been a challenge. I developed a general method for training recurrent neural networks (RNNs) of spiking model neurons and used it to construct spiking networks capable of performing tasks previously beyond our reach. My method established a key conceptual link between spiking networks and more commonly used ‘rate’ networks that illustrated how spiking networks can be constructed to perform virtually any task modeled with rate networks. Additionally, I used my approach to understand the mechanistic origin of latent factors (e.g., principal components), a burgeoning statistical framework for describing neural population activity. I constructed spiking RNNs that produced latent factors derived from neural recordings in the primary motor cortex, and illustrated how the factors are constructed within the network’s synaptic connectivity. A second challenge for real and artificial neural circuits is performing tasks with long temporal dependencies. I invented a novel network training method called full-FORCE that can build networks able to perform tasks over behaviorally relevant timescales. full-FORCE has largely supplanted its widely-used predecessor, ‘FORCE’, as the premier, non-gradient-based method for training RNNs, and multiple groups have used it to address their own unique research questions.

[**Key paper**: The centrality of population-level factors to network computation is demonstrated by a versatile approach for training spiking networks](https://doi.org/10.1016/j.neuron.2022.12.007)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="https://ars.els-cdn.com/content/image/1-s2.0-S0896627322010807-gr1_lrg.jpg"
  headline="Methods for constructing biophysically detailed and data-constrained artificial neural networks"
  text=text
%}