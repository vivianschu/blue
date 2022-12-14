---
title: Team
nav:
  order: 3
  tooltip: lab members
---

# <i class="fas fa-users"></i>Team

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pdf"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{:.center}

## Alumni

Our outstanding lab alumni are listed below, including former graduate students, PDFs, and also undergraduate students that have co-authored publications. If you are missing from this list, apologies, and please let us know.

{% include list.html 
   data="members"
   component="portrait"
   filters="group: alumni"
   style="small"
%}
{:.center}

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/photo.jpg"
  link1="https://nasa.gov/"
  tooltip1="Cool Foundation"

  image2="images/photo.jpg"
  link2="https://nasa.gov/"
  tooltip2="Cool Institute"

  image3="images/photo.jpg"
  link3="https://nasa.gov/"
  tooltip3="Cool Initiative"

  image4="images/photo.jpg"
  link4="https://nasa.gov/"
  tooltip4="Cool Foundation"

  image5="images/photo.jpg"
  link5="https://nasa.gov/"
  tooltip5="Cool Institute"

  image6="images/photo.jpg"
  link6="https://nasa.gov/"
  tooltip6="Cool Initiative"
%}
