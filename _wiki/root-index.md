---
layout  : wikiindex
title   : wiki
toc     : true
public  : true
comment : false
updated : 2024-04-19 14:45:58 +0900
regenerate: true
---

* TOC
{:toc}

[[/book-log-2024]]

[[/video-log-2024]]

## [[article]]
* [[/article/successful-study/20240419-study-idea]]
* [[/article/successful-study/20240419-first-plan]]

---

## blog posts
<div>
    <ul>
{% for post in site.posts %}
    {% if post.public == true %}
        <li>
            <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">
                {{ post.title }}
            </a>
        </li>
    {% endif %}
{% endfor %}
    </ul>
</div>

