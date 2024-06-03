---
---

# Meshinchi Lab Website

Welcome to the Meshinchi Lab at Fred Hutch. Led by Soheil Meshinchi, M.D., Ph.D., our research laboratory is studying genomic expression of acute myeloid leukemia-restricted targets on the cell surface that are ideal for immunotherapeutic targeting with chimeric antigen receptor T-cell (CAR T) therapies, as well as identifying and validating target genes for further immunotherapy development.

{% include section.html %}

## Highlights

{% capture text %}

Take a look at some of the publications from the Meshinchi lab.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-left"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Publications"
  text=text
%}

{% capture text %}

Take a look at some of the projects which are ongoing in the lab.

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

Meet the members of the Meshinchi lab.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-left"
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
