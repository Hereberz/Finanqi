<script>
	export let open = false
</script>

<aside class="absolute w-50 h-full bg-gray-200 border-r-2 shadow-lg" class:open>
	<nav class="column-1 p-12 text-xl">
		<a class="block" href="/resume">Resumo</a>
		<a class="block" href="/in">Entradas</a>
		<a class="block" href="/out">Saídas</a>
		<a class="block" href="/params">Params</a>
        </nav>
        </aside>

<style>
	aside {
		left: -200%;
		transition: left 0.3s ease-in-out
	}
	
	.open {
		left: 0
	}
</style>