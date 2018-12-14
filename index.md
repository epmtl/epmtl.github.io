## Welcome to EPMTL repositories

Gathering a couple of projects or tests written in various languages.

### Projects
Here is the list of projects:
{% for repository in site.github.public_repositories %}
  {% if repository.name != 'epmtl.github.io' %}
  * [{{ repository.name }}]({{ repository.html_url }})
  {% endif %}
{% endfor %}
