<script>
  import Saos from "saos";
  export let projectData = [];
</script>

{#each projectData as data, index}
  <Saos animation={`from-left ${index*0.2}s ease-in`}>
    <span
      id="span"
      class="flex flex-col max-w-[17rem]"
    >
      <span class="border-[#ABB2BF] border-solid border p-[1rem]">
        <img loading="lazy" width="300" height="300" src={data.img} alt="img" />
      </span>

      <span
        class="border-[#ABB2BF] border-solid border text-[#ABB2BF] p-[1rem]"
      >
        {data.tech}
      </span>

      <span
        class="flex gap-[0.5rem] border-[#ABB2BF] border-solid border flex-col p-[0.8rem]"
      >
        <span class="text-[24px] font-medium">
          {data.name}
        </span>

        <span class="text-[#ABB2BF]">
          {data.desc}
        </span>

        <span class="flex gap-[1rem]">
          {#if data.github.length != 0}
            <a
              href={data.github}
              class="text-[18px] border-2 border-solid border-[#C778DD] py-[0.3rem] px-[0.6rem] hover:bg-[#C778DD] hover:bg-opacity-20"
            >
              Github
            </a>
          {/if}

          {#if data.live.length != 0}
            <a
              href={data.live}
              class="text-[18px] border-2 border-solid border-[#C778DD] py-[0.3rem] px-[0.6rem] hover:bg-[#C778DD] hover:bg-opacity-20"
            >
              Live
            </a>
          {/if}
        </span>
      </span>
    </span>
  </Saos>
{/each}

<style>
  @keyframes -global-from-left {
    0% {
      opacity: 0;
    }
    100% {
      opacity: 1;
    }
  }
</style>
