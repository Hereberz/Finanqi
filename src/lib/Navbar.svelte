<script>
	import Logo from './liblib/logo.svelte';
	import Hamburguer from './liblib/Hamburguer.svelte';
	
	export let sidebar = false
</script>

<header class="flex justify-between border-none bg-crust p-2 border-b-2">
	<nav class="flex">
        <Hamburguer bind:open={sidebar}/>
		<Logo/>	
	</nav>
</header>