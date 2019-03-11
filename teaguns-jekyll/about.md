---
layout: page
title: Blog
permalink: /blog
---

<section>

	{% for post in site.posts %}
		{% unless post.next %}
			<h3>{{ post.date | date: '%Y' }}</h3>
		{% else %}
			{% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
			{% capture nyear %}{{ post.next.date | date: '%Y' }}{% endcapture %}
			{% if year != nyear %}
				<h3>{{ post.date | date: '%Y' }}</h3>
			{% endif %}
		{% endunless %}

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
	<p>Oops, no blog posts yet. First one is coming really soon. Subscribe below to get notified!</p>

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