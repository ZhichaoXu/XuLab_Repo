---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>People


{% include section.html dark=true %}

The Xu Lab is expected to open in Spring 2025 and will offer positions at all levels. Whether you are a scientist eager to explore cancer genomics and gene regulation, a PhD student seeking training in genome engineering and 3D genomics, or simply curious about participating in and learning more about research in functional genomics, we welcome your interest and collaboration.

{% 
  include link.html 
  icon="fas fa-hands-helping"
  text="Join the Team" 
  link="positions"
  style="button" 
%} 
{:.center}

{% include section.html %}
## Current Members
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
  filters="role: current-" 
%}

