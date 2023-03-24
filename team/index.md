---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team
{:.center}

Our lab members come from several schools at Penn: Engineering, Wharton, and Medicine. We tackle interdisciplinary problems and strive to promotes respect, equity, and diversity. The team includes investigators, postdocs, staff, students at PhD, Masters, and Undergraduate levels.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi, group: " %}
{% include list.html data="members" component="portrait" filters="role: coi, group: " %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: " %}
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}
{% include list.html data="members" component="portrait" filters="role: masters, group: " %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}
{% include list.html data="members" component="portrait" filters="role: visit-student, group: " %}
{% include list.html data="members" component="portrait" filters="role: project-manager, group: " %}
{:.center}

{% include section.html background="images/banner.jpg" dark=true%}

# Join
{:.center}

We have multiple RA positions available for undergrad and graduate students already enrolled at UPenn on applying natural language and image processing to health, especially but not limited to – global mental health, vaccine acceptance, and firearms safety. If you’re interested send me an email with your CV and Academic Transcript at sharathg at cis dot upenn dot edu. 

### Post Doctoral Researcher

We have an opening for a postdoc position at the intersection of CS x Psychology. The position is for a 1 year term with the possibility to renew it. 

{% include button.html link="https://bit.ly/penn_postdoc_css" text="Apply Now" %}
{:.center}

{% include section.html %}

# Alumni
{:.center}
These are past lab members who have moved on to other school programs, new jobs, or elsewhere.

{% include list.html data="members" component="portrait" filters="role: masters, group: alum" %}
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

# Current Collaborators
{:.center}

Lorem ipsum.

{% include list.html data="collabs" component="portrait-collab" %}