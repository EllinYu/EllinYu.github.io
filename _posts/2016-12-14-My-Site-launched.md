---
layout: post
title: "My Site"
date: 2016-12-14
---
<h1> <img src="http://www.yavf.or.th/bitrix/1%E0%B9%90/sakura_falling.gif" alt="sakura"/>{{ page.title }} <img src="http://www.yavf.or.th/bitrix/1%E0%B9%90/sakura_falling.gif" alt="sakura"/></h1>
	<ul class="posts">

	  {% for post in site.posts %}
	    <li><span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
	  {% endfor %}
	</ul>
        
