<script>
  import Calculator from './components/Calculator.svelte'
</script>

<header>
  <h1>Svelte calculator</h1>
</header>

<main>
  <Calculator/>
</main>

<style global>



  :global(body) {
    background-color: #eee;
    margin: 0;
    font-family: sans-serif;
  }

  :global(*, *::before, *::after) {
    box-sizing: border-box;
  }



</style>
