---
title: Who we are
nav:
  order: 2
  tooltip: People
---

# <i class=“fas fa-users”></i> About Brian

{%
  include list.html
  data=“members”
  component=“portrait”
  filters=“role: pi”
%}

{% include section.html %}

# <i class="fas fa-users"></i> Current members

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}

{% include section.html %}

## Collaborators

**<span style="color:red">Collaborations are central to our research.</span>** <span style="color:red">Here are some of the research groups we currently work with</span>


{% capture text %}
The <a href="https://www.youngerlaboratory.org/">Younger Lab</a> at BU studies the olfactory system of mosquitos.
{:.center}
{% endcapture %}

{%
  include feature.html
  image="https://images.squarespace-cdn.com/content/v1/614de94a4f15316f922c40fa/1632515659512-BOFFGN0HMEG2YYZC57C6/i-bRCrWX6-X3.jpg?format=2500w"
  headline="Meg Younger"
  text=text
%}

{% capture text %}
The <a href="https://economolab.org/">Economo Lab</a> at BU studies the neural circuits of movement.
{:.center}
{% endcapture %}

{%
  include feature.html
  image="https://economolab.files.wordpress.com/2018/10/algorithms_circuits2.jpg?w=1290&h=548"
  headline="Mike Economo"
  text=text
%}

{% capture text %}
The <a href="https://www.howe-lab.org/">Howe Lab</a> at BU studies the role of the basal ganglia in learning.
{:.center}
{% endcapture %}

{%
  include feature.html
  image="https://images.squarespace-cdn.com/content/v1/5ac91e45b10598283d2083c7/1541078552001-KT1WG4TMTY6C23HLHE31/DendritesMSN.jpg?format=2500w"
  headline="Mark Howe"
  text=text
%}

{% capture text %}
The <a href="https://www.scottcognitionlab.com/">Scott Lab</a> at BU studies cognition and develops new technologies to study it.
{:.center}
{% endcapture %}

{%
  include feature.html
  image="https://images.squarespace-cdn.com/content/v1/5aee1aeb4611a046d4fd485c/1527460358719-L0WCSDRZMR5YBKBXT9PG/Untitled.gif?format=2500w"
  headline="Ben Scott"
  text=text
%}

{% include section.html %}

## Interested in joining?
### Prospective PhDs
If you are interested in conducting research within the group as a PhD student, please apply to the BU BME [PhD program](https://www.bu.edu/eng/academics/explore-degree-programs/phd-in-biomedical-engineering/) or the BU graduate program in [neuroscience](  https://www.bu.edu/neuro/academics/graduate/). Unfortunately, I cannot respond to individual email inquiries about joining my group as a PhD student. If you are interested, apply to one of the programs above. 

### Admitted PhD students
My rotation project policy is to encourage you to bring your **own ideas** to the table. I try not to 'assign' projects (although I will if needed)!

### Postdocs
If you are interested in a postdoc, please [email Brian](mailto:bddepasq@bu.edu).  

<!--- ## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/photo.jpg"
  link1="https://nasa.gov/"
  tooltip1="Cool Foundation"

%}
-->