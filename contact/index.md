---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We’re always excited to hear from curious and motivated students who want to explore new ideas and contribute to our research. Whether you’re looking for a thesis project, an internship, or simply want to gain hands‑on experience, our lab offers opportunities to learn, collaborate, and grow.

If you’re passionate about science, eager to develop new skills, and ready to work in a supportive team environment, we’d love to hear from you. Email us directly — let’s start a conversation about how you can be part of our work.

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
