<script lang="ts">

	import Toggle from './toggle.svelte'
	import * as config from '$lib/config'

</script>

<nav>
	<a href="/" class="title" title="Init">
		<b>{config.title}</b>
	</a>

	<ul class="links">
		<li>
			<a href="/coverLetter">Cover Letter</a>
		</li>
		<li>
			<a href="/curriculum">Curriculum</a>
		</li>
		<li>
			<a href="/about">About</a>
		</li>
		<li>
			<a href="/contact">Contact</a>
		</li>
		<li>
			<a href="#blog">Blog</a>
		</li>
		<li>
			<a href="/rss.xml" target="_blank">RSS</a>
		</li>
	</ul>

	<Toggle />
</nav>

<style>
	nav {
		padding-block: var(--size-7);
	}

	.links {
		margin-block: var(--size-7);
	}

	a {
		color: inherit;
		text-decoration: none;

	}

	nav .title {
		font-size: 22px;
		background: linear-gradient(to right, #2657eb, #de6161); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
  		-webkit-background-clip: text;
  		-webkit-text-fill-color: transparent;
	}

	@media (min-width: 768px) {
		nav {
			display: flex;
			justify-content: space-between;
		}

		.links {
			display: flex;
			gap: var(--size-7);
			margin-block: 0;
		}
	}
</style>
