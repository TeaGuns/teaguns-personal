---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
<!--Subscribe-->

<!--Recent Posts-->
<!--<section>
  <div class="row">
  <h3>Recent Posts</h3>
  {% for post in site.posts offset: 0 limit: 1  %}
  <ul>
      <li>
        <div class="post-date">
          <span>{{ post.date | date: "%b %d" }}</span>
        </div>
        <div class="title">
          <a href="{{ post.url | prepend: site.baseurl | prepend: site.url }}">{{ post.title }}</a>
        </div>
      </li>
    </ul>
    {% endfor %}
  </div>
</section>-->
<!--Projects-->
<section>
  <div id="projects" class="row">
    <h3>Projects</h3>
    <p><a target="_blank" href="https://modagrate.com/">Modagrate</a> is an automatic moderation tool designed for Slack, Telegram and Discord communities.</p>
    <p><a href="#">CommSponsor</a> helps connect communities with awesome brands and companies wanting to sponsor them.</p>
  </div>
</section>
<section>
  <div class="row">
    <div id="mc_embed_signup">
    <p class="sub">If you'd like to get updates on my projects and blog posts, then you can subscribe here.</p>
      <form action="https://macredd.us20.list-manage.com/subscribe/post?u=4c1f9f7bdbd2d24ace466d96e&amp;id=ee025b4ea1" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
        <div id="mc_embed_signup_scroll">
          <div class="mc-field-group">
            <input type="email" placeholder="Your Email" value="" name="EMAIL" class="required email" id="mce-EMAIL">
          </div>
          <div id="mce-responses" class="clear">
            <div class="response" id="mce-error-response" style="display:none"></div>
            <div class="response" id="mce-success-response" style="display:none"></div>
          </div>    <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
          <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_4c1f9f7bdbd2d24ace466d96e_ee025b4ea1" tabindex="-1" value=""></div>
          <div class="clear"><input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button"></div>
        </div>
      </form>
      <p>I promise to never spam you. Max 1 email per week.</p>
    </div>
  </div>
</section>
<section>
  <div class="container work">
    <div class="row center">
      <div class="col-12">
        <h3 id="workTogether">Let's Work Together</h3>
      </div>
      <div class="col-3">
        <p>✉️ <a target="_blank" href="mailto:m@credd.in">m@credd.in</a></p>
      </div>
      <div class="col-3">
        <p>📄 <a target="_blank" href="https://www.dropbox.com/s/43fzol6juiiidsq/Mac%20Resume.pdf?dl=0">Résumé</a></p>
      </div>
      <div class="col-3 ">
        <p>👨‍💻 <a target="_blank" href="https://dribbble.com/TheTeaGuns">View Selected Work</a></p>
      </div>
    </div>
  </div>
  <div id='tr-footer'></div>
      <!-- make reveal calls last -->
    <script>
      ScrollReveal().reveal('.row',{duration:1e3,distance:"40px",easing:"cubic-bezier(0.5, -0.01, 0, 1.005)",origin:"bottom",interval:150})
    </script>
</section>
