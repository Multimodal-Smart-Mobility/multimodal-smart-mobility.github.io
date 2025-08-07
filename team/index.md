---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team


#### Academic Staff
{% include list.html data="members" component="portrait" filter="role == 'pi'"  %}
#### Postdoctoral Fellow
{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}
#### Ph.D./MPhil Student
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}
#### Research/Project Assistant
{% include list.html data="members" component="portrait" filter="role == 'ra'" %}
#### Undergraduate Student
{% include list.html data="members" component="portrait" filter="role == 'under'" %}
#### Visiting Scholar/Student
{% include list.html data="members" component="portrait" filter="role == 'visiting'" %}
#### Alumni
{% include list.html data="members" component="portrait" filter="role == 'alumni'" %}
