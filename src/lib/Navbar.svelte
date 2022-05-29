<script>
	import Logo from './liblib/logo.svelte';
	import Hamburguer from './liblib/Hamburguer.svelte';
	import Menu from './liblib/Menu.svelte';
	
	export let sidebar = false
</script>

<header class="flex justify-between bg-gray-200 p-2 items-center text-gray-600 border-b-2">
	<nav class="flex">
        <Hamburguer bind:open={sidebar}/>
		<Logo/>	
	</nav>
	
	<Menu/>
</header>