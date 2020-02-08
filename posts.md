---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
---
<!--Recent Posts-->
<section>
  <div class="mini-section">
    <div class="row flex-center">
        <h1 class="m-0"><i class="fad fa-paper-plane"></i></h1>
        <h5 class="m-0 mt-1"><span class="text-bold">Posts</span></h5>
    </div>
    <div class="row">
      <p>Things I've written. Mostly about startups, but sometimes about other random things. Not a lot here (yet!). I'm trying to start writing as a habit in 2020.</p>
    </div>
    <div class="row">
     {% for post in site.posts offset: 0 %}
      <p><a href="{{ post.url }}" class="hover-link">{{ post.title }}</a> </p>
      {% endfor %} 
    </div>
  </div>
  </section>