<script>
  export let variant = null;
  export let size = null;
</script>

<button 
  class="button"
  class:primary={variant === 'primary'}
  class:secondary={variant === 'secondary'}
  class:large={size === 'large'}
>
  <slot></slot>
</button>

<style>

.button {
  background-color: #A0A0A0;
  border: none;
  border-radius: 50%;
  width: 64px;
  height: 64px;
  display: inline-flex;
  justify-content: center;
  align-items: center;
  font-size: 1.5rem;
}

.primary {
  background-color: #FF9500;
  color: #fff;
}

.secondary {
  background-color: #313131;
  color: #fff;
}

.large {
  width: 140px;
  border-radius: 40px;
  justify-content: flex-start;
  padding-left: 24px;
  color: #fff;
}

</style>