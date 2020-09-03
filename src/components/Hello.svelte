<div>{$_('Hello, world!')}</div>

<script lang="ts">
  import { _ } from 'svelte-i18n'
</script>

<style lang="scss">
  @import '../styles/variables';

  div {
    text-align: center;
    color: $hello-color;
  }

  // To modify something outside the scope, use :global()
  :global(p) {
    font-size: 2rem;
  }
</style>
