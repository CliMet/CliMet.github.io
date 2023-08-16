---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

If you have questions, please feel free to contact us.

{%
  include button.html
  type="email"
  text="CliMetGroup@gmail.com"
  link="CliMetGroup@gmail.com"
%}
{%
  include button.html
  type="phone"
  text="(852)3469-3101"
  link="+852-3469-3101"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Hong+Kong+University+of+Science+and+Technology+(HKUST)/@22.3355431,114.2704449,14.44z/data=!4m6!3m5!1s0x3404046bc19c7e15:0x2bedd58f9cf841be!8m2!3d22.338017!4d114.266618!16zL20vMDFucHYz?entry=ttu"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
