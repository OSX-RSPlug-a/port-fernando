<script lang="ts">
	import { formatDate } from '$lib/utils'
	import * as config from '$lib/config'

	import Index from './index/+page.svelte'

	export let data
</script>

<svelte:head>
	<title>{config.title}</title>
</svelte:head>

<div>

	<Index />

	<h2 id="blog">Blog posts</h2>

</div>

<section>

	<ul class="posts">
		{#each data.posts as post}
			<li class="post">
				<a href={post.slug} class="title">{post.title}</a>
				<p class="date">{formatDate(post.date)}</p>
				<p class="description">{post.description}</p>
			</li>
		{/each}
	</ul>
	
</section>

<style>
	
	.posts {
		display: grid;
		gap: var(--size-7);
	}

	.post {
		max-inline-size: var(--size-content-3);
	}

	.post:not(:last-child) {
		border-bottom: 1px solid var(--border);
		padding-bottom: var(--size-7);
	}

	.title {
		font-size: var(--font-size-fluid-3);
		text-transform: capitalize;
	}

	.date {
		color: var(--text-2);
	}

	.description {
		margin-top: var(--size-3);
	}

	h2 {
		margin-top: 1in;
		margin-bottom: 1in;
	}

</style>
