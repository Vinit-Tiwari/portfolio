<script>
  import { fade, fly } from "svelte/transition";
  export let url;
</script>

{#key url}
  <div
    class="flex flex-col w-full h-full"
    in:fly={{ y: -50, duration: 250, delay: 100 }}
  >
    <slot />
  </div>
{/key}
