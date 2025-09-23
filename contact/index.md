---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

On computational front, we are looking for applicants interested in theory and algorithm development for neural data analysis, as well as development of a versatile data pipeline with user-friendly front-end and documentation. Ideal candidates should have experience and interests in one or more of the following areas: signal processing; machine learning; system identification; computational neuroscience; Python development; prior experience with MEG and/or EEG is not required but would be a plus.

On experimental front, we are looking for applicants interested in EEG/ MRI studies, who are willing to develop and/or run congnitive experiment protocol for healthy volunteers. Ideal candidates should have experience or interests in one or more of the following areas: computational psychology, cognitive neuroscience; prior experience with Python or MATLAB is not required but would be a plus. 

{%
  include button.html
  type="email"
  text="proloy.das@nbrc.ac.in"
  link="proloy.das@nbrc.ac.in"
%}
{%
  include button.html
  type="phone"
  text="1242845405"
  link="1242845405"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/RRw6Q3WCzgXvBaNh6"
%}

{% include section.html %}

{% capture col1 %}

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d7023.684589582758!2d76.9393395704791!3d28.333373919400753!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x390d3c0d7a2feb63%3A0xf15c5a2d9397fdfc!2sNational%20Brain%20Research%20Centre!5e0!3m2!1sen!2sin!4v1739008510491!5m2!1sen!2sin" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1%}
<!-- {% include cols.html col1=col1 col2=col2 %} -->

<!-- {% include section.html dark=true %} -->

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
 
<!-- {% include cols.html col1=col1 col2=col2 col3=col3 %} -->
