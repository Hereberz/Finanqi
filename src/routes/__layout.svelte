<script>
  import "../app.css";
  import Navbar from '../lib/Navbar.svelte';
  import Sidebar from '../lib/Sidebar.svelte';
  const title = "Home Page";
  let open = false;
</script>

<Sidebar bind:open/>
<Navbar bind:sidebar={open}/>

<svelte:head>
  <title>{title}</title>
  <link href="https://unpkg.com/tailwindcss@^1.0/dist/tailwind.min.css" rel="stylesheet"/>
</svelte:head>
  <slot />