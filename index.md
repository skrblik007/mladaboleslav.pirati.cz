---
layout: page
section: blog
description: Výchozí stránka táborské pirátské buňky s nejnovějšími články a základním rozcestníkem.
keywords: piráti, tábor, organizace, transparence, politika
---


<section class="hero alert-box secondary">
	<div class="row">
		<div class="small-8 columns">
			<p>
				Chceš se setkat s Piráty z Moravskoslezského kraje?<br/>
				Je ti blízký pirátský program / ideje?<br/>
				Máš kuráž a taky chceš transparentnější a modernější město, kraj a stát?<br/>
				Zaujaly tě naše akce? Přijď do OPICE!
			</p>

			<a href="/kontakt/" class="primary button test">Kde nás najdeš →</a>

		</div>

		<div class="small-4 columns">
			<img src="/static/budpirat-small.png" alt="buď pirát - ucle sam grafika" />
		</div>
	</div>
</section>


## Aktuality <i class="fa fa-newspaper-o"></i>

{% for post in site.posts limit:20 %}  
{% include articlesumary.html %}
{% endfor %}  
