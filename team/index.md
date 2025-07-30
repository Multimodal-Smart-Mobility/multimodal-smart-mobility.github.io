---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team


#### Faculty
{% include list.html data="members" component="portrait" filters="role == 'pi'"  %}
#### Postdoctoral Fellows
{% include list.html data="members" component="portrait" filters="role == 'postdoc'" %}
#### Ph.D./MPhil Students
{% include list.html data="members" component="portrait" filters="role == 'phd'" %}
#### Research/Project Assistant
{% include list.html data="members" component="portrait" filters="role == 'ra'" %}
#### Undergraduate Students
{% include list.html data="members" component="portrait" filters="role == 'under'" %}
#### Visiting Scholar/Students
{% include list.html data="members" component="portrait" filters="role == 'visiting'" %}
#### Alumni
{% include list.html data="members" component="portrait" filters="role == 'alumni'" %}
