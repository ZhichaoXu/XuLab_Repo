---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>People

{% include section.html %}
## Current Members
{% 
  include list.html  
  data="members"  
  component="portrait"  
  filters="role: pi" 
%}
