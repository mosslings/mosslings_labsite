---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We’re always excited to hear from curious and motivated students who want to explore new ideas and contribute to our research. 
If you’re passionate about science, eager to develop new skills, and ready to work in a supportive team environment, we’d love to hear from you. Email us directly.

Master’s students in STEM fields from Jammu & Kashmir, Ladakh, and Northeast India can apply through the <a href="https://en.vikaspedia.in/viewcontent/education/internship-opportunities-for-students/biotrail-summer-research-and-discovery-program-at-the-school-of-biology,-iiser-thiruvananthapuram?lgn=en" target="_blank">BioTrail</a> program of IISER-TVM and work with us.

{%
  include button.html
  type="email"
  text="mosslab1102@gmail.com"
  link="mosslab1102@gmail.com"
%}
{%
  include button.html
  type="phone"
  text="+91(0)471-2778501"
  link="+91-471-277-8501"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/@8.6814153,77.1368791,21z?entry=ttu&g_ep=EgoyMDI2MDUwNi4wIKXMDSoASAFQAw%3D%3D"
%}

{% comment %}
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
{% endcomment %}
