---
title: Homepage
layout: default
---

Icepick is a public `LICENSE` for software that requires transparency, accountability, and independence from those who run and develop the software for others.

[Read the latest version for yourself.](/versions/1.0.0)

[Review old versions.](/versions)

[Send feedback and patches via GitHub.](https://github.com/kemitchell/icepick)

<h2 id=projects>Projects</h2>

<ul class="projects">
{% for project in site.projects reversed %}
<li>
    <a href="{{project.url}}">{{project.title}}</a>{% if project.description %}, {{project.description}}{% endif %}{% if project.language %}, in {{project.language}}{% endif %}
  </li>
  {% endfor %}
</ul>

<p>To list your project, send a pull request <a href="https://github.com/kemitchell/icepicklicense.org">via GitHub</a>.</p>
