---
layout: default
---

I am a software engineer with work experience in quantitative trading and Big Tech. This
site serves primarily as a blog of my personal studies in math and computer science, as
well as anything else that interests me.

### Recent Posts

<ul class="posts">
    {% for post in site.posts limit:5 %}
        <li>
            <span class="post-date">{{ post.date | date: "%b %d, %Y" }}</span>
            ::
            <a class="post-link" href="{{ post.url }}">{{ post.title }}</a>
        </li>
    {% endfor %}
</ul>