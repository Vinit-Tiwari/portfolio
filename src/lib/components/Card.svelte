<script>
  export let projectData=[];
  export let smallProjects=[];
</script>

{#each projectData as data}
  <span class="flex flex-col max-w-[20rem]">
    <span class="border-[#ABB2BF] border-solid border p-[1rem]"> Image </span>

    <span class="border-[#ABB2BF] border-solid border text-[#ABB2BF] p-[1rem]">
      {data.tech}
    </span>

    <span
      class="flex gap-[0.5rem] border-[#ABB2BF] border-solid border flex-col p-[1rem]"
    >
      <span class="text-[24px] font-medium">
        {data.name}
      </span>

      <span class="text-[#ABB2BF]">
        {data.desc}
      </span>

      <span class="flex gap-[1rem]">
        <button
          class="text-[18px] border-2 border-solid border-[#C778DD] py-[0.3rem] px-[0.6rem] hover:bg-[#C778DD] hover:bg-opacity-20"
        >
          Github
        </button>

        <button
          class="text-[18px] border-2 border-solid border-[#C778DD] py-[0.3rem] px-[0.6rem] hover:bg-[#C778DD] hover:bg-opacity-20"
        >
          Live
        </button>
      </span>
    </span>
  </span>
{/each}

{#each smallProjects as data}
  <span class="flex flex-col max-w-[20rem]">
    <span class="border-[#ABB2BF] border-solid border p-[1rem]"> Image </span>

    <span class="border-[#ABB2BF] border-solid border text-[#ABB2BF] p-[1rem]">
      {data.tech}
    </span>

    <span
      class="flex gap-[0.5rem] border-[#ABB2BF] border-solid border flex-col p-[1rem]"
    >
      <span class="text-[24px] font-medium">
        {data.name}
      </span>

      <span class="text-[#ABB2BF]">
        {data.desc}
      </span>

      <span class="flex gap-[1rem]">
        <button
          class="text-[18px] border-2 border-solid border-[#C778DD] py-[0.3rem] px-[0.6rem] hover:bg-[#C778DD] hover:bg-opacity-20"
        >
          Github
        </button>

        <button
          class="text-[18px] border-2 border-solid border-[#C778DD] py-[0.3rem] px-[0.6rem] hover:bg-[#C778DD] hover:bg-opacity-20"
        >
          Live
        </button>
      </span>
    </span>
  </span>
{/each}
