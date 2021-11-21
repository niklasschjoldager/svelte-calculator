<script>
  import Button from './Button.svelte'
</script>


<section class="calculator">
  <div>0</div>

  <div class="controls">
    <Button>AC</Button>
    <Button>+/-</Button>
    <Button>%</Button>
    <Button variant="primary">÷</Button>
    <Button variant="secondary">7</Button>
    <Button variant="secondary">8</Button>
    <Button variant="secondary">9</Button>
    <Button variant="primary">x</Button>
    <Button variant="secondary">4</Button>
    <Button variant="secondary">5</Button>
    <Button variant="secondary">6</Button>
    <Button variant="primary">-</Button>
    <Button variant="secondary">1</Button>
    <Button variant="secondary">2</Button>
    <Button variant="secondary">3</Button>
    <Button variant="primary">+</Button>
    <Button variant="secondary" size="large">0</Button>
    <Button variant="secondary">.</Button>
    <Button variant="primary">=</Button>
  </div>
</section>

<style>
  .calculator {
    background-color: #000;
    max-width: 324px;
    margin: 0 auto;
  }

  .controls {
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
    padding: 12px;
  }
</style>