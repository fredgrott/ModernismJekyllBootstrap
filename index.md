---
layout: front
title:
---

<div class="row">
      <div class="col col-lg-8">
        <h2>Blog</h2>
        <<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
<p><a class="btn btn-default" href="archive.html">View archive &raquo;</a></p>
      </div>
      
    </div>
<div class="row">
      <div class="col col-lg-4">
        <h2>Bio</h2>
        <p>In a galaxy far, far away </p>
        <p><a class="btn btn-default" href="./bio/index.html">View details &raquo;</a></p>
      </div>
      <div class="col col-lg-4">
        <h2>Folio</h2>
        <p>I have several folios, thus a list of sorts of those folios </p>
        <p><a class="btn btn-default" href="./folio/index.html">View details &raquo;</a></p>
     </div>
    </div>
    <div class="row">
      <div class="col col-lg-4">
        <h2>Research</h2>
        <p>Slides and articles in many different areas. </p>
        <p><a class="btn btn-default" href="./research/index.html">View details &raquo;</a></p>
      </div>
      <div class="col col-lg-4">
        <h2>Hacking</h2>
        <p>My free-wheeling collection of hacking projects. </p>
        <p><a class="btn btn-default" href="./hacking/index.html">View details &raquo;</a></p>
     </div>
    </div>
    

