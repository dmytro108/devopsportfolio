---
layout: page
title: About
permalink: /about/
weight: 3
---

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRT7B4RgxazjT5sh-Rcu-OtAfwtF52Zl-v2-GhfjUceOZmiIupzMaYVHMX8Nmy4OzGjGD8RVedSFTzJ/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>