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
  filters="role: pi, group: current"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: staff, group: current"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pdf, group: current"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: grad, group: current"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad, group: current"
%}
{:.center}

## Alumni

Our outstanding lab alumni are listed below, including former graduate students, PDFs, and undergraduate students. If you are missing from this list, apologies, and please let us know.

{% include list.html 
   data="members"
   component="portrait"
   filters="group: alumni"
   style="small"
%}
{:.center}
