---
title: Resources
permalink: /resources/
---

{% assign people_sorted = site.resource | sort: 'started' %}
{% assign role_array = "active|maintenance|deprecated" | split: "|" %}

{% for role in role_array %}

{% assign people_in_role = people_sorted | where: 'position', role %}

<!-- Skip section if there's nobody -->
{% if people_in_role.size == 0 %}
  {% continue %}
{% endif %}

<div class="pos_header">
{% if role == 'active' %}
<h3>Active Resource Projects</h3>
 {% elsif role == 'maintenance' %}
<h3>Maintained projects</h3>
 {% elsif role == 'deprecated' %}
<h3>Deprecated Projects</h3>
{% endif %}
</div>

{% if role != 'deprecated' %}
<div class="content list people">
  {% for profile in people_sorted reversed %}
    {% if profile.position contains role %}
      <div class="list-item-people">
        <p class="list-post-title">
          {% if profile.avatar %}
            <a href="{{ site.baseurl }}{{ profile.url }}"><img class="profile-thumbnail" src="{{site.baseurl}}/images/software/{{profile.avatar}}"></a>
          {% else %}
            <a href="{{ site.baseurl }}{{ profile.url }}"><img class="profile-thumbnail" src="http://evansheline.com/wp-content/uploads/2011/02/facebook-Storm-Trooper.jpg"></a>
          {% endif %}
          <a class="name" href="{{ site.baseurl }}{{ profile.url }}">{{ profile.name }}</a>
        </p>
      </div>    
    {% endif %}
  {% endfor %}
</div>
<hr>

{% endif %}
{% endfor %}
