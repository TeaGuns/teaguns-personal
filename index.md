---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<!--Recent Posts-->
<section class="body-center">
  <div class="mini-section">
    <div class="row flex-center">
        <h1 class="m-0"><i class="fad fa-cat-space"></i></h1>
        <h5 class="m-0 mt-1">Hey I'm <span class="text-bold">Mac Reddin</span></h5>
    </div>
      <div class="row">
        <h1>I like making things while drinking excessive amounts of tea. Currently building community at <a href="https://www.commsor.com" class="hover-link" target="_blank">Commsor</a>.</h1>
        <p>On the side, I also enjoy <a href="/investing" class="hover-link">investing</a> in and supporting other founders.</p>
      </div>
      <div class="row">
        <div class="hide-sm">
          <div class="latest-post">
            {% for post in site.posts offset: 0 limit: 1 %}
            <p>Latest Post: <a href="{{ post.url }}" class="hover-link no-wrap">{{ post.title }}</a> </p>
            {% endfor %} 
            <a class="hover-link" href="/posts">View All Posts</a>
          </div>
        </div>
         <div class="latest-post show-sm text-center">
          {% for post in site.posts offset: 0 limit: 1 %}
          <p>Latest Post: <a href="{{ post.url }}" class="hover-link">{{ post.title }}</a> </p>
          {% endfor %} 
          <a class="hover-link" href="/posts">View All Posts</a>
        </div>
      <div class="row nav-links hide-sm">  
        <p>Get in touch 👉</p>
        <a target="_blank" class="hover-link" href="https://twitter.com/TheTeaGuns">Twitter</a>
        <!--<a class="hover-link" data-formkit-toggle="4ee15e5259" href="https://macreddin.ck.page/4ee15e5259">Newsletter</a>-->
        <a target="_blank" class="hover-link" href="https://www.linkedin.com/in/mac-reddin-7a275716b/">LinkedIn</a>
        <a class="hover-link" href="mailto:m@credd.in">m@credd.in</a>
      </div>
      <div class="row show-sm text-center">  
        <p>Get in touch 👇</p>
        <div>
          <a target="_blank" class="hover-link mobile-link" href="https://twitter.com/TheTeaGuns">Twitter</a>
        </div>
        <!--<div>
          <a class="hover-link mobile-link" data-formkit-toggle="4ee15e5259" href="https://macreddin.ck.page/4ee15e5259">Newsletter</a>
        </div>-->
        <div>
          <a target="_blank" class="hover-link mobile-link" href="https://www.linkedin.com/in/mac-reddin-7a275716b/">LinkedIn</a>
        </div>
        <div>
          <a class="hover-link mobile-link" href="mailto:m@credd.in">m@credd.in</a>
        </div>
      </div>
    </div>
