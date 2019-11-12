<script>
  // Imports
  import Tailwindcss from "./Tailwindcss.svelte";

  // Exports
  export let name;
</script>

<style>
  h1 {
    color: purple;
  }
</style>

<Tailwindcss />
<h1>Hello {name}!</h1>
