---
layout: home
---

<div class="index-content home">
    <div class="section">
        <ul class="artical-cate">
            <li class="on" style="text-align:left"><a href="/"><span>Home</span></a></li>
            <li style="text-align:center"><a href="/myresearch"><span>Me & My Research</span></a></li>
            <li style="text-align:right"><a href="/opinion"><span>Opinions</span></a></li>
</ul>

        <div class="cate-bar"><span id="cateBar"></span></div>

        <p class="artical-list"> 
        Welcome to Jin Lian（廉晋）'s web ! 
        I am a Postdoc researcher working in Light in Complex  Systems group (<a href="http://touchablephysics.com/nanolinx/">LINX</a>), Unversity of Utrecht.  In this web, you can find information of <a href="/myresearch">My Research</a> and my personal <a href="/opinion">Opinions</a> (some of them are in Chinese).
        </p>
        <br/>     
        <p class="artical-list"> 
        I hope you enjoy visiting here! 
        </p>
       <br/>      
        <p class="artical-list" align="left"> 
        Jin </p>
        <br/>
        <br/>

      <ul class="artical-list">
        {% for post in site.categories.home %}
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


