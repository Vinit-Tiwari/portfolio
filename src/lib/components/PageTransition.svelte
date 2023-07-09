<script>
  import { fly } from "svelte/transition";
  export let url;
</script>

{#key url}
  <div
    class="flex flex-col w-full h-full"
    in:fly={{ y: -200, duration: 250, delay: 300 }}
  >
    <slot />
  </div>
{/key}
