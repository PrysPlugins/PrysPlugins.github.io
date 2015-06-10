---
title: Pry's Plugins
---

## My Repositories

Below is a list of repositories containing various WordPress plugins. Each title is a link that you can click to view the repository directly in GitHub.

{% for repository in site.github.public_repositories %}
### [{{ repository.name | replace:'-',' ' | replace:'_',' ' }}]({{ repository.html_url }}){:target="_blank"}

{{ repository.description }}

{% endfor %}
