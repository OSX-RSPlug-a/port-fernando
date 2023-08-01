<script lang="ts">

	import * as config from '$lib/config'
	import 'open-props/buttons';

</script>

<footer>
	<p>{config.title} &copy {new Date().getFullYear()} <a href="/" title="Init"> Initial page</a></p>
</footer>

<style>

	footer {
		padding-block: var(--size-7);
		border-top: 1px solid var(--border);
	}

	p {
		color: var(--text-2);
	}

	p a {
		padding-left: 25px;
		align-self: center;
		
	}

</style>
