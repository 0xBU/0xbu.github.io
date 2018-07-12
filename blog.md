---
layout: blog_layout
---

{% for post in site.posts %}
<article class="preview">
    <header>
        <h2 class="post-title">
            <a href="{{ post.url }}">  {{ post.title }} </a>
        </h2>
    </header>
    <section class="post-section">
        <p>
            {{ post.excerpt }}
        </p>
        <p class="readmore">
            <a href="{{ post.url }}">
                Read More
                <span class="glyphicon glyphicon-circle-arrow-right"></span>
            </a>
        </p>
    </section>
</article>
{% endfor %}

