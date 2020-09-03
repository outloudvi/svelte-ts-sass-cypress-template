<main>
  <p>Welcome to {project_name}!</p>
  <Hello />
</main>

<script lang="ts">
  import { onMount } from 'svelte'
  import Hello from './components/Hello.svelte'

  export let project_name: string

  onMount(() => {
    console.log('Hello, Svelte')
  })
</script>

<style lang="scss">
  p {
    text-align: center;
  }
</style>
