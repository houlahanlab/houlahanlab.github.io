---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are highly-motivated, interdiscplinary scientists that sit at the intersection of cancer biology, computer science and machine learning. If you are interested in a graduate student or postdoctoral position in the Houlahan lab, please reach out via email. If you are an undergraduate researcher, please fill out this [form](https://forms.gle/RJhA8V1PuDmeuFzE9). 

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html %}

## Alumni

- Farida Abdelmalek - Bioinformatics Co-op Student
- Alia Chaudhary - Undergraduate Researcher

{% include section.html background="images/background.jpg" dark=true %}


{% include section.html %}

{% capture content %}

<!-- {% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %} -->

{% endcapture %}

{% include grid.html style="square" content=content %}
