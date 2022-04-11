<!-- __layout.svelte -->
<script>
  import Header from '$lib/components/Header.svelte'
  import '$lib/styles/main.css'
</script>

<Header />
<!-- The rest of the HTML here -->

<!-- __layout.svelte -->


<main>
  <slot />
</main>

<footer>&copy; 2022 Maryam</footer>


<style>
  footer{
    display:flex;
    justify-content: center;
    background: black;
      color: white;
      padding: 1rem;
    font-size: large;
  }
</style>