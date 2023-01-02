---
layout: page
---


<div class="row">
{% for post in site.posts %}
{% if post.layout == 'post' %}
  <div class="col-lg-3 col-md-6 col-sm-6 col-xs-12">
    <div class="card-wrapper">
            <a href="{{post.url}}">
            <div class="card">
            <img src="{{site.url}}/assets/images/{{post.picture}}" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">{{post.title}}</h5>
                <p class="card-text">{{post.description}}</p>
            </div>
            </div>
            </a>
    </div>
  </div>
{% endif %}
{% endfor %}
</div>

