<script>
   	import Navbar from '../lib/Navbar.svelte';
	import Sidebar from '../lib/Sidebar.svelte';
    import Form from '../cards/form.svelte';
    import "../app.css";

    const title = "HMMMMMMMM";
    let open = false;
</script>
<Sidebar bind:open/>
<Navbar bind:sidebar={open}/>
<svelte:head>
    <title>{title}</title>
    <link href="https://unpkg.com/tailwindcss@^1.0/dist/tailwind.min.css" rel="stylesheet"/>
</svelte:head>

<h1 class="text-3xl font-bold underline">Tô só tentandoajeitar isso aqui</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<Form/>