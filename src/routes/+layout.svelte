<!-- src/routes/+layout.svelte -->
<script>
  import "../app.css";
  import { page } from '$app/stores';
</script>

{#if $page.url.pathname.endsWith('/')}
<link
  rel="stylesheet" 
  href="https://cdn.jsdelivr.net/npm/@picocss/pico@1/css/pico.min.css"
/>
{/if}

<slot />