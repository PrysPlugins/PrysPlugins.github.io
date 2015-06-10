---
title: Pry's Plugins
permalink: /index.html
---

## My Repositories

{% for repository in site.github.public_repositories %}
### [{{ repository.name | replace:'-',' ' | replace:'_',' ' }}]({{ repository.html_url }})

{{ repository.description }}

{% endfor %}
