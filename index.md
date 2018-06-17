---
layout: home
title: {{site.title}}
permalink: /
---

{% include header.html %}

{% assign homepage = true %}
<main id="site-main" class="site-main outer">
	<div class="inner">
		<div class="post-feed">
    		{% include posts.html %}
		</div>
  </div>
</main>

{% include footer.html %}