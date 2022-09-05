<script>
	import breadcrump from './components/breadcrump.svelte';
	import footer from './components/footer.svelte';

	let component = breadcrump;
	let props = {active_page: ''};
	 
</script>

<svelte:component this={component} {...props}/>

<p>Welcome to our homepage!</p>
<p>This ia simple web app with two pages which has been created with the SvelteKit.</p>
<p>Follow this link to go the <a href="/about">About</a> page.</p>

<svelte:component this={footer} {...props}/>