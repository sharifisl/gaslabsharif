---
---

<!-- # sharifisl's Website -->

Generative AI Systems Lab at Sharif University of Technology brings together passionate students exploring the frontiers of artificial intelligence. Supervised by Dr. Hamid Beigy, our team focuses on innovative research in generative models and AI-driven systems. We foster a collaborative and inclusive environment where new ideas and diverse perspectives are valued.

{% include section.html %}

## Highlights

{% capture text %}
We conduct research in artificial intelligence, focusing on machine learning and deep learning to develop innovative and intelligent systems.
{% include button.html link="research" text="See what we've published" icon="fas fa-arrow-right" flip=true %} {:.center} 
{% endcapture %} 
{% include feature.html image="images/research.jpg" link="research" title="Generative AI + Creativity → Innovation" text=text %}



{% endcapture %}

{%
  include feature.html
  image="images/research.jpg"
  link="research"
  title="See what we've published"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

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
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
