<script>
  import { fly } from "svelte/transition";
  export let url;
</script>

{#key url}
  <div
    class="flex flex-col w-full h-full"
    in:fly={{ y: -50, duration: 250, delay: 300 }}
    out:fly={{ y: -50, duration: 250 }}
  >
    <slot />
  </div>
{/key}
