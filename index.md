---
layout: default
---

Hey ! This is Thomas George, studying deep learning at [MILA](https://mila.umontreal.ca/) under the supervision of [Pascal Vincent](http://www.iro.umontreal.ca/~vincentp/).

## Notes for course ift6268 computer vision
Here are some notes I took while reading papers related to vision during the course ift6268 by Roland Memisevitch:
<ul>
  {% for post in site.categories.ift6268 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> ({{ post.date | date_to_string }})
    </li>
  {% endfor %}
</ul>

## Notes for course ift6266 deep learning
Here are some blog posts I wrote for the project in the deep learning course ift6266 by Yoshua Bengio:
<ul>
  {% for post in site.categories.ift6266 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> ({{ post.date | date_to_string }})
    </li>
  {% endfor %}
</ul>
