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
  filters="role: staff"
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
  filters="role: grad"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad"
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
