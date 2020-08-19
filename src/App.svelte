<script lang="ts">
  import Tailwindcss from './Tailwindcss.svelte';
  export let name: string;
</script>

<Tailwindcss />

<main>
  <h1 class="mt-4">Hello {name}!</h1>
  <p>
    Visit the
    <a href="https://svelte.dev/tutorial">Svelte tutorial</a>
    to learn how to build Svelte apps.
  </p>
</main>
