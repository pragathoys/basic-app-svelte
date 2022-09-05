<script>
	import breadcrump from '../components/breadcrump.svelte';
	import footer from '../components/footer.svelte';

	let component = breadcrump;
	let props = {active_page: ''};
	 
</script>

<svelte:component this={component} {...props}/>

<p>This is an internal page powered by Svelte!!</p>

<svelte:component this={footer} {...props}/>