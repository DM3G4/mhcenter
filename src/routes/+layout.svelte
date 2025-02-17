<script>
  import "@picocss/pico/css/pico.css"

  let { children } = $props()
</script>

<main class="container">
  {@render children()}
</main>

<style>
  main {
    margin-top: 24px;
  }
</style>
