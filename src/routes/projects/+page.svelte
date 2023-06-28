<script>
  import projectData from "$lib/DecentProjects.js";
  import smallProjects from "$lib/SmallProjects.js";
  import Card from "../../lib/components/Card.svelte";
</script>

<span
  class="text-white flex px-[0.5rem] pt-[4rem] w-full gap-[1rem] max-w-[70rem] m-auto pb-[1rem] flex-col"
>
  <span class="max-w-[66rem] p-[0.5rem] w-full m-auto">
    <span class="flex flex-col">
      <span class="flex text-[33px]">
        <p class="text-[#C778DD]">/</p>
        projects
      </span>

      <p class="text-[#ABB2BF] text-[18px]">List of my projects</p>
    </span>

    <span class="flex flex-col p-[1rem] max-w-[66rem] w-full m-auto gap-[1rem]">
      <span class="flex gap-[1rem] items-center">
        <span class="flex text-[33px]">
          <p class="text-[#C778DD]">#</p>
          decent
        </span>

        <div
          class="hidden lg:flex h-[0.1rem] w-[100vw] max-w-[10rem] bg-[#C778DD]"
        />
      </span>

      <span class="flex flex-wrap gap-[0.5rem]">
        <Card {projectData} />
      </span>
    </span>

    <span class="flex flex-col p-[1rem] max-w-[66rem] w-full m-auto gap-[1rem]">
      <span class="flex gap-[1rem] items-center">
        <span class="flex text-[30px]">
          <p class="text-[#C778DD]">#</p>
          small-projects
        </span>

        <div
          class="hidden lg:flex h-[0.1rem] w-[100vw] max-w-[20rem] bg-[#C778DD]"
        />
      </span>

      <span class="flex flex-wrap gap-[0.5rem]">
        <Card {smallProjects} />
      </span>
    </span>
  </span>
</span>
