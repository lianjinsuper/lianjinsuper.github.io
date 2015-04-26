---
layout: home
---

<div class="index-content blog">
    <div class="section">
        <ul class="artical-cate">
            <li class="on" style="text-align:left"><a href="/"><span>Abount Me</span></a></li>
            <li style="text-align:center"><a href="/myresearch"><span>My Research</span></a></li>
            <li style="text-align:center"><a href="/opinion"><span>Opinions</span></a></li>
</ul>

        <div class="cate-bar"><span id="cateBar"></span></div>

        <p class="artical-list"> 
        Welcome to Jin Lian（廉晋）'s web ! 
        I am a PhD researcher in Complex photonic systems group (<a href="http://cops.nano-cops.com/">COPS</a>), Unversity of Twente. In this web, you can find information of <a href="/myresearch">My Research</a> and my personal <a href="/opinion">Opinion</a> (some of them are in Chinese).
        </p>
         <p class="artical-list">
        </p>       
        <p class="artical-list"> 
        I hope you enjoy visiting here! 
        </p>
        <p class="artical-list">
        </p>       
        <p class="artical-list"> 
        Jin </p>
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


