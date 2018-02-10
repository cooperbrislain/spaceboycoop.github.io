---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
---

## Posts ##
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## Repos ##
<ul>
    {% for repository in site.github.public_repositories %}
        <li>
            <a href="{{ repository.url }}">{{ repository.name }}</a>
        </li>
    {% endfor %}
</ul>
