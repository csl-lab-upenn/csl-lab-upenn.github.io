---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team
{:.center}

Our lab members come from several schools at Penn: Engineering, Wharton, and Medicine. We tackle interdisciplinary problems and strive to promote respect, equity, and diversity. The team includes investigators, postdocs, staff, and students at PhD, Masters, and Undergraduate levels.

{% include section.html %}

{% for role in site.data.member_roles %}
  {% capture role_filters %}role: {{ role }}, group: {% endcapture %}
  {% include list.html data="members" component="portrait" filters=role_filters %}
{% endfor %}
{:.center}

{% include section.html background="images/banner.jpg" dark=true%}

# Join
{:.center}

We have RA positions available for undergrad and graduate students enrolled at UPenn interested in applying NLP and machine learning to health — with a focus on global mental health, vaccine acceptance, and firearms safety. Send your CV and academic transcript to sharathg at cis dot upenn dot edu.

{% include section.html %}

# Alumni
{:.center}
These are past lab members who have moved on to other school programs, new jobs, or elsewhere.

{% include list.html data="members" component="portrait" filters="group: alum" %}
{:.center}

{% include section.html %}

# Funding
{:.center}

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html

  image1="images/nimhd.png"
  link1="https://reporter.nih.gov/search/xr8dfej1VEKkBA8K5-mxBQ/project-details/10630593"
  tooltip1="National Institute on Minority Health and Health Disparities"

  image2="images/pennglobal.jpeg"
  link2="https://blog.seas.upenn.edu/sharath-guntuku-receives-penn-global-grant-to-continue-vaccine-attitudes-research-in-india/"
  tooltip2="Penn Global"

  image3="images/wbg.jpeg"
  link3="https://documents1.worldbank.org/curated/en/099125001262248277/pdf/P1770020efdd8702708f9d0c44309d295c4.pdf"
  tooltip3="World Bank Group"
 
%}

{% include section.html %}

# Current Collaborators
{:.center}

{% include list.html data="collabs" component="portrait-collab" %}
