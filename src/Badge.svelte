<script>
  export let type;
</script>

<style>
  .c-badge {
    background: #DDD;
    color: #999;
    border-radius: 1.2rem;
    padding: 0.3rem 1.2rem;
    font-size: 1.3rem;
  }
</style>
  
<div
  class="c-badge"
  class:c-badge--success={type == "success"}
>
  <slot></slot>
</div>