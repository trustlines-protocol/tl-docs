---
layout: default
---

<!-- Section -->
<section>
	<header class="major">
		<h2>Trustlines Network</h2>
	</header>
	<div class="features">
		<article>
			<span class="icon fa-sitemap"></span>
			<div class="content">
				<h3>Trustlines Foundation</h3>
				<p>The <a href="https://www.trustlines.foundation/" target="_blank">Trustlines Foundation</a> is supporting research, development, deployment, governance and adoption of the Trustlines Protocol, with a focus on acting in a supporting role within the Trustlines Network.</p>
			</div>
		</article>
		<article>
			<span class="icon fa-code"></span>
			<div class="content">
				<h3>Protocol Developers</h3>
				<p>The Trustlines Network is an open-source project with multiple contributors. If you want to contribute to the protocol, check out the <a href="(https://dev.trustlines.network/" target="_blank">documentation</a> and <a href="https://github.com/trustlines-protocol" target="_blank">GitHub</a> to get started.</p>
			</div>
		</article>
		<article>
			<span class="icon fa-link"></span>
			<div class="content">
				<h3>Validators‍</h3>
				<p>Trustlines validators will validate blocks on the Trustlines Blockchain. The Trustlines Blockchain will be a minimal viable Proof-of-Stake (mPoS) Ethereum sidechain.</p>
			</div>
		</article>
		<article>
			<span class="icon fa-server"></span>
			<div class="content">
				<h3>Access & Infrastructure Providers</h3>
				<p>Relay servers provide easy access to the smart contract systems for mobile phone users. They help to locate the paths in the Trustlines Network for transactions.</p>
			</div>
		</article>
		<article>
			<span class="icon fa-usd"></span>
			<div class="content">
				<h3>Community Currency Projects</h3>
				<p>Communities will be able to deploy their own community currencies on the Trustlines Network.</p>
			</div>
		</article>
		<article>
			<span class="icon fa-laptop"></span>
			<div class="content">
				<h3>App Developers‍</h3>
				<p>App developers can use the Trustlines infrastructure out of the box as a base layer to build their apps on top of the Trustlines Protocol. Please see our <a href="(https://dev.trustlines.network/" target="_blank">documentation</a> for further details.</p>
			</div>
		</article>
		<article>
			<span class="icon fa-users"></span>
			<div class="content">
				<h3>Users</h3>
				<p>We envision a future, where anyone will be able to use the Trustlines Network. All that should be needed is a mobile phone and a friend to get on-boarded onto the network.</p>
			</div>
		</article>
	</div>
</section>

<!-- Section -->
<section>
	<header class="major">
		<h2>Latest updates</h2>
	</header>
	<div class="posts">
		<article>
			<ul>
				{% for post in site.posts limit:1 %}
						<a href="{{ post.url | absolute_url | absolute_url }}" class="image"><img src="{{ post.image }}"/></a>
						{{ post.date | date: '%B %d, %Y'}}
						<h3>{{ post.title }}</h3>
						{{ post.excerpt }}
							<a href="{{ post.url | absolute_url }}" class="button">More</a>
				{% endfor %}
			</ul>
		</article>
		<article>
			<ul>
				{% for post in site.posts limit:1 offset:1 %}
						<a href="{{ post.url | absolute_url }}" class="image"><img src="{{ post.image }}"/></a>
						{{ post.date | date: '%B %d, %Y'}}
						<h3>{{ post.title }}</h3>
						{{ post.excerpt }}
							<a href="{{ post.url | absolute_url }}" class="button">More</a>
				{% endfor %}
			</ul>
		</article>
		<article>
			<ul>
				{% for post in site.posts limit:1 offset:2 %}
						<a href="{{ post.url | absolute_url }}" class="image"><img src="{{ post.image }}"/></a>
						{{ post.date | date: '%B %d, %Y'}}
						<h3>{{ post.title }}</h3>
						{{ post.excerpt }}
							<a href="{{ post.url | absolute_url }}" class="button">More</a>
				{% endfor %}
			</ul>
		</article>
		<article>
			<ul>
				{% for post in site.posts limit:1 offset:3 %}
						<a href="{{ post.url | absolute_url }}" class="image"><img src="{{ post.image }}"/></a>
						{{ post.date | date: '%B %d, %Y'}}
						<h3>{{ post.title }}</h3>
						{{ post.excerpt }}
							<a href="{{ post.url | absolute_url }}" class="button">More</a>
				{% endfor %}
			</ul>
		</article>
	</div>
</section>
