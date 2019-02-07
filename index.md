---
published_date: "2019-02-07 12:20:01 +0000"
layout: home.liquid
is_draft: false
---
{% for post in collections.posts.pages %}
<article style="background-color:#{{post.tags[1]}};">   
        <a href="{{ post.permalink }}"> 
        <div class="article-content">
            <h2 class="article-title">{{post.title}}</h2>
            <span class="pub-detail" style="background-color:white;font-size:0.9em;color:black;font-weight:500;border:solid 2px #000;border-radius:100px;padding:1px 5px 1px 5px;">December 23, 2013</span>
            <span class="pub-detail" style="background-color:white;font-size:0.9em;color:black;font-weight:500;border:solid 2px #000;border-radius:100px;padding:1px 5px 1px 5px;">{{post.tags[0]}}</span>
        </div>
        </a>
</article> 

{% endfor %}
