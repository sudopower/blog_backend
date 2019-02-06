---
published_date: "2019-02-06 10:29:28 +0000"
layout: home.liquid
is_draft: false
---
{% for post in collections.posts.pages %}
<article style="background-color:#{{post.tags[1]}};">   
        <a href="{{ post.permalink }}"> 
        <div class="article-content">
            <h2 class="article-title">{{post.title}}</h2>
            December 23, 2013 by {{post.tags[0]}}
        </div>
        </a>
</article>

{% endfor %}
