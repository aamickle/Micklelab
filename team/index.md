---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team
Learn more about the team by clicking on their picture!

{% include section.html %}

## PI
{% include list.html data="members" component="portrait" filter="role == 'pi'" %}

## Postdocs
{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}

## Students
{% include list.html data="members" component="portrait" filter="role == 'student'" %}

## Staff
{% include list.html data="members" component="portrait" filter="role == 'staff'" %}

## Collaborators
{% include list.html data="members" component="portrait" filter="role == 'collaborator'" %}

## Alumni
{% include list.html data="members" component="portrait" filter="role == 'Alumni'" %}

{% include section.html background="images/painting2024_5.jpg" dark=true %}
