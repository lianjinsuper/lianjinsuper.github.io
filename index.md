---
layout: home
---

<div class="index-content blog">
    <div class="section">
        <ul class="artical-cate">
            <li class="on" style="text-align:left"><a href="/"><span>Abount me</span></a></li>
            <li style="text-align:left"><a href="/myrearch"><span>My research</span></a></li>
            <li style="text-align:left"><a href="/blog"><span>Blog</span></a></li>
</ul>

        <div class="cate-bar"><span id="cateBar"></span></div>

        <ul class="artical-list">
        {% for post in site.categories.aboutme %}
            <li>
                <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
                <div class="title-desc">{{ post.description }}</div>
            </li>
        {% endfor %}
        </ul>
    </div>
    <div class="aside">
    </div>
</div>
