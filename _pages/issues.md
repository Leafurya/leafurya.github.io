---
layout: archive
title: "Issues"
permalink: /issues/
author_profile: true
sidebar:
  nav: "issues"
---
---

<link href="{{'assets/css/home.css'|relative_url}}" rel="stylesheet">
<div class="post_platform">
	<div style="flex: 1">
		<ul class="card-list">
			{% assign issues_posts = site.categories.issues %}
			{% for post in issues_posts limit:5 %}
				<li>
				<a href="{{ post.url }}">{{ post.title }}</a><br>
				{% for tag in post.tags %}
					<span class="tag">{{ tag }}</span>
				{% endfor %}
				<br>
				<span class="date">{{ post.date | date: "%Y-%m-%d" }}</span>
				</li>
			{% endfor %}
		</ul>
	</div>
</div>