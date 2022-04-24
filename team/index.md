---
title: Team
nav:
  order: 3
  tooltip: About our team
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
  filters="role: programmer"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: mascot-d"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: mascot-c"
%}
{:.center}

{% include section.html dark=true %}

We work with a wide range of outstanding groups from around the world, and we're always on the lookout for new and unique perspectives.
We want to push the frontier of data science and train the next generation of data scientists.

{%
  include link.html
  icon="fas fa-hands-helping"
  text="Join the Team"
  link="join"
  style="button"
%}
{:.center}

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html

  image1="images/funding/usaid.svg"
  link1="https://www.usaid.gov/"
  tooltip1="US Agency for International Development"

  image2="images/funding/nifa.jpg"
  link2="https://nasa.gov/"
  tooltip2="USDA National Institute of Food and Agriculture"

  image3="images/funding/nsf.png"
  link3="https://nsf.gov/"
  tooltip3="National Science Foundation"
%}
