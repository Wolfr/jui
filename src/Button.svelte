<script>
  export let variant;
  export let as;
  export let href;
</script>

<style>
  .c-button {
    background: #DDD;
    color: #999;
    padding: 1rem;
    border-radius: 0.3rem;
  }
</style>

{#if as == "button"}
  <button class="c-button">
    <slot></slot>
  </button>
{:else}
  <a href="{href}" class="button">
    <slot></slot>
  </a>
{/if}