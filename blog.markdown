---
layout: page
---


<div class="row">
{% for post in site.posts %}
  <div class="col-md-3 card-wrapper">
        <div class="card" style="width: 18rem;">
        <div class="card-body">
            <h5 class="card-title">{{post.title}}</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="{{post.url}}" class="btn btn-xs btn-link">{{post.title}}</a>
        </div>
        </div>
    </div>
{% endfor %}
</div>

