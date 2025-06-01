<script>
  import Card from "../lib/components/Card.svelte";
  import projectData from "$lib/ProjectData.js";
</script>

<span class="text-white flex pt-[4rem] pb-[1rem] flex-col">
  <span
    class="flex flex-col lg:flex-row m-auto p-[2rem] max-w-[70rem] items-center justify-center"
  >
    <span class="flex flex-col h-full gap-[2rem] items-start">
      <span class="flex gap-[0.3rem] flex-wrap max-w-[45rem] text-[35px] font-medium">
        Hi, I'm Vinit, a 
        <p class="text-[#C778DD] h-min">Software Engineer</p>
        specializing in 
        <p class="text-[#C778DD] h-min">automation, developer tooling, full-stack web systems</p>
      </span>
      <span class="text-[#ABB2BF] text-[20px] max-w-[30rem]">
        Code Craftsman | Automating Systems, Building Tools, and Bridging Teams
      </span>

      <a
        href="mailto: vinittiwari1912@gmail.com"
        class="text-[20px] border-2 border-solid border-[#C778DD] py-[0.3rem] px-[0.6rem] hover:bg-[#C778DD] hover:bg-opacity-20"
      >
        Contact me !!
      </a>
    </span>

    <span class=" flex flex-col items-center gap-[0.2rem]">
      <span class="relative">
        <img
          class="absolute top-[2rem] z-0"
          width="170"
          height="170"
          alt="img"
          src="./images/logo1.svg"
        />

        <img
          rel="preload"
          class="relative z-20"
          width="415"
          height="350"
          src="./images/profilePhoto.svg"
          alt="profileImage"
        />

        <img
          class="hidden lg:flex absolute z-20 top-[15rem] right-[1rem]"
          src="./images/Dots.svg"
          alt="img"
        />
      </span>

      <span
        class="flex items-center gap-[0.3rem] border py-[0.2rem] pl-[1rem] pr-[4rem]"
      >
        <div class="w-[1rem] h-[1rem] bg-[#C778DD]" />
        <span class="text-[18px]"> Currently working in Siemens </span>
      </span>
    </span>
  </span>

  <span class="flex py-[2rem] px-[1rem] items-center">
    <span class="flex flex-col items-end m-auto">
      <span
        class="flex relative border py-[1.5rem] text-[18px] lg:text-[24px] px-[1.2rem]"
      >
        <svg
          class="absolute top-[-13px]"
          width="42"
          height="29"
          viewBox="0 0 42 29"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <rect width="41.472" height="28.704" fill="#282C33" />
          <path
            d="M18.56 19.616C18.56 21.0453 18.0373 22.2507 16.992 23.232C15.968 24.2133 14.72 24.704 13.248 24.704C11.7333 24.704 10.4747 24.2133 9.472 23.232C8.49067 22.2507 8 21.0453 8 19.616C8 18.9333 8.096 18.208 8.288 17.44C8.48 16.672 8.864 15.68 9.44 14.464L14.4 4H19.2L16.544 15.584C17.1413 16.0107 17.6213 16.576 17.984 17.28C18.368 17.9627 18.56 18.7413 18.56 19.616ZM32.8 19.616C32.8 21.0453 32.2773 22.2507 31.232 23.232C30.1867 24.2133 28.9387 24.704 27.488 24.704C26.016 24.704 24.768 24.2133 23.744 23.232C22.7413 22.2507 22.24 21.0453 22.24 19.616C22.24 18.9333 22.336 18.208 22.528 17.44C22.72 16.672 23.1147 15.68 23.712 14.464L28.704 4H33.472L30.784 15.584C31.4027 16.0107 31.8933 16.576 32.256 17.28C32.6187 17.9627 32.8 18.7413 32.8 19.616Z"
            fill="#ABB2BF"
          />
        </svg>

        Code is like humor. When you have to explain it, it's bad.
        <svg
          class="absolute left-[85%] top-[80%]"
          width="42"
          height="29"
          viewBox="0 0 42 29"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <rect width="41.472" height="28.704" fill="#282C33" />
          <path
            d="M18.56 19.616C18.56 21.0453 18.0373 22.2507 16.992 23.232C15.968 24.2133 14.72 24.704 13.248 24.704C11.7333 24.704 10.4747 24.2133 9.472 23.232C8.49067 22.2507 8 21.0453 8 19.616C8 18.9333 8.096 18.208 8.288 17.44C8.48 16.672 8.864 15.68 9.44 14.464L14.4 4H19.2L16.544 15.584C17.1413 16.0107 17.6213 16.576 17.984 17.28C18.368 17.9627 18.56 18.7413 18.56 19.616ZM32.8 19.616C32.8 21.0453 32.2773 22.2507 31.232 23.232C30.1867 24.2133 28.9387 24.704 27.488 24.704C26.016 24.704 24.768 24.2133 23.744 23.232C22.7413 22.2507 22.24 21.0453 22.24 19.616C22.24 18.9333 22.336 18.208 22.528 17.44C22.72 16.672 23.1147 15.68 23.712 14.464L28.704 4H33.472L30.784 15.584C31.4027 16.0107 31.8933 16.576 32.256 17.28C32.6187 17.9627 32.8 18.7413 32.8 19.616Z"
            fill="#ABB2BF"
          />
        </svg>
      </span>

      <span
        class="py-[1rem] border text-[16px] lg:text-[20px] px-[1.2rem] text-[#ABB2BF]"
        >- Cory House</span
      >
    </span>

    <div class="hidden lg:flex border-t border-b border-l w-[5rem] h-[5rem]" />
  </span>

  <!-- PROJECT SECTION -->
  <span class="flex flex-col m-auto w-full max-w-[66rem] p-[1rem]">
    <span
      class="flex gap-[1rem] gap-[1rem] items-center w-full justify-between"
    >
      <span class="flex gap-[1rem] items-center">
        <span class="flex text-[33px]">
          <p class="text-[#C778DD]">#</p>
          projects
        </span>

        <div
          class="hidden lg:flex h-[0.1rem] w-[100vw] max-w-[30rem] bg-[#C778DD]"
        />
      </span>

      <a href="/projects" class="flex">View all ~~></a>
    </span>

    <span class="flex p-[1rem] flex-wrap gap-[1rem] justify-start">
      <Card {projectData} />
    </span>
  </span>

  <!-- SKILLS SECTION -->
  <span class="flex flex-col p-[1rem] max-w-[66rem] w-full m-auto gap-[1rem]">
    <span class="flex gap-[1rem] items-center">
      <span class="flex text-[33px]">
        <p class="text-[#C778DD]">#</p>
        skills
      </span>

      <div class="flex h-[0.1rem] w-[100vw] max-w-[10rem] bg-[#C778DD]" />
    </span>

    <span class="flex items-center justify-between gap-[1rem]">
      <span class="hidden lg:flex relative w-full max-w-[25rem] h-[20rem]">
        <img
          class="absolute top-[60%] left-[15%] z-0"
          width="100"
          alt="img"
          height="100"
          src="./images/logo1.svg"
        />

        <div
          class="flex absolute w-[5rem] h-[5rem] left-[65%] border-[#ABB2BF] border-solid border"
        />

        <img
          class="absolute top-[10%] left-[5%] z-20"
          width="70"
          height="70"
          alt="img"
          src="./images/Dots.svg"
        />

        <div
          class="flex absolute w-[3rem] h-[3rem] border-[#ABB2BF] border-solid border left-[80%] top-[70%]"
        />

        <img
          class="absolute top-[50%] left-[55%] z-20"
          width="70"
          height="70"
          alt="img"
          src="./images/Dots.svg"
        />
      </span>

      <span
        class=" items-center px-[0.5rem] w-full flex-wrap md:flex-row lg:flex-row flex gap-[1rem]"
      >
        <span class="flex flex-col max-w-[15rem]">
          <div
            class="px-[1rem] py-[0.5rem] border-[#ABB2BF] border-solid border"
          >
            Languages
          </div>

          <div
            class="px-[1rem] py-[0.3rem] text-[#ABB2BF] border-[#ABB2BF] border-solid border"
          >
            JavaScript, TypeScript, Python, PHP
          </div>
        </span>

        <span class="flex flex-col gap-[1rem]">
          <span class="flex flex-col max-w-[15rem]">
            <div
              class="px-[1rem] py-[0.5rem] border-[#ABB2BF] border-solid border"
            >
              Databases
            </div>

            <div
              class="px-[1rem] py-[0.3rem] text-[#ABB2BF] border-[#ABB2BF] border-solid border"
            >
              MongoDB, Firebase, Strapi
            </div>
          </span>

          <span class="flex flex-col max-w-[15rem]">
            <div
              class="px-[1rem] py-[0.5rem] border-[#ABB2BF] border-solid border"
            >
              Other
            </div>

            <div
              class="px-[1rem] py-[0.3rem] text-[#ABB2BF] border-[#ABB2BF] border-solid border"
            >
              SASS, Tailwind, Nginx, Git + Github, Husky
            </div>
          </span>
        </span>

        <span class="flex flex-col gap-[1rem]">
          <span class="flex flex-col max-w-[15rem]">
            <div
              class="px-[1rem] py-[0.5rem] border-[#ABB2BF] border-solid border"
            >
              Backend Frameworks
            </div>

            <div
              class="px-[1rem] py-[0.3rem] text-[#ABB2BF] border-[#ABB2BF] border-solid border"
            >
              Nodejs, Expressjs
            </div>
          </span>

          <span class="flex flex-col max-w-[15rem]">
            <div
              class="px-[1rem] py-[0.5rem] border-[#ABB2BF] border-solid border"
            >
              Frameworks
            </div>

            <div
              class="px-[1rem] py-[0.3rem] text-[#ABB2BF] border-[#ABB2BF] border-solid border"
            >
              Sveltekit, Next, React, Remix, Solid, Astro, Django, Laravel
            </div>
          </span>
        </span>
      </span>
    </span>
  </span>

  <!-- ABOUT ME SECTION   -->
  <span class="max-w-[66rem] p-[1rem] w-full m-auto">
    <span class="flex gap-[1rem] items-center">
      <span class="flex text-[33px]">
        <p class="text-[#C778DD]">#</p>
        about-me
      </span>

      <div
        class="hidden lg:flex h-[0.1rem] w-[100vw] max-w-[30rem] bg-[#C778DD]"
      />
    </span>

    <span
      class="flex flex-wrap p-[1rem] gap-[1rem] items-center justify-center lg:justify-between"
    >
      <span class="flex flex-col max-w-[33rem] gap-[2rem]">
        <span class="flex text-[17px] flex-col gap-[1rem]">
          <p class="text-[#ABB2BF]">Hello, I'm Vinit!</p>
          <p class="text-[#ABB2BF]">
            A passionate Software Engineer with a knack for solving real-world problems through automation, developer tooling, and full-stack development.
          </p>

          <p class="text-[#ABB2BF]">
            Currently, I work at Siemens Mobility, where I independently lead automation initiatives that enhance developer productivity, streamline CI/CD workflows, and reduce manual overhead. My work ranges from writing Python automation scripts and Golang-based ETL pipelines to integrating APIs and tools like GitLab, SonarQube, and Pocketbase.
          </p>
        </span>

        <a
          href="/about-me"
          class="text-[18px] w-max border-2 border-solid border-[#C778DD] py-[0.3rem] px-[0.6rem] hover:bg-[#C778DD] hover:bg-opacity-20"
        >
          Read more ~~>
        </a>
      </span>

      <span class="relative border-b-2 border-[#C778DD]">
        <img
          class="absolute top-[70%] left-[65%] z-20"
          width="70"
          height="70"
          alt="img"
          src="./images/Dots.svg"
        />

        <img
          class="absolute top-[10%] left-[5%] z-20"
          width="70"
          height="70"
          alt="img"
          src="./images/Dots.svg"
        />

        <img
          src="./images/profilePhoto2.svg"
          width="300"
          height="300"
          alt="img"
        />
      </span>
    </span>
  </span>

  <!-- CONTACTS SECTION-->
  <span class="m-auto w-full max-w-[66rem] p-[1rem]">
    <span class="flex gap-[1rem] items-center">
      <span class="flex text-[33px]">
        <p class="text-[#C778DD]">#</p>
        contacts
      </span>

      <div class="flex h-[0.1rem] w-[100vw] max-w-[10rem] bg-[#C778DD]" />
    </span>

    <span
      class="flex flex-wrap items-center justify-center gap-[1rem] lg:justify-between p-[1rem]"
    >
      <span class="text-[#ABB2BF] text-[17px] max-w-[25rem]">
        I'm interested in freelance opportunities. However, if you have other
        request or question, don't hesitate to contact me
      </span>

      <span
        class="flex justify-evenly flex-col border-[#ABB2BF] border-solid border gap-[0.5rem] py-[0.5rem] px-[1rem]"
      >
        <p>Message me here</p>

        <a
          target="_blank"
          href="https://www.linkedin.com/in/vinit-tiwari1912"
          class="text-[#ABB2BF] hover:text-white flex gap-[0.4rem] w-fit items-center"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            data-name="Layer 1"
            fill="#ABB2BF"
            stroke-width="0.5"
            stroke="#282C33"
            class="w-6 h-6"
            viewBox="0 0 24 24"
            id="linkedin"
            ><path
              d="M20.47,2H3.53A1.45,1.45,0,0,0,2.06,3.43V20.57A1.45,1.45,0,0,0,3.53,22H20.47a1.45,1.45,0,0,0,1.47-1.43V3.43A1.45,1.45,0,0,0,20.47,2ZM8.09,18.74h-3v-9h3ZM6.59,8.48h0a1.56,1.56,0,1,1,0-3.12,1.57,1.57,0,1,1,0,3.12ZM18.91,18.74h-3V13.91c0-1.21-.43-2-1.52-2A1.65,1.65,0,0,0,12.85,13a2,2,0,0,0-.1.73v5h-3s0-8.18,0-9h3V11A3,3,0,0,1,15.46,9.5c2,0,3.45,1.29,3.45,4.06Z"
            /></svg
          >

          vinit-tiwari1912
        </a>

        <span class="text-[#ABB2BF] flex gap-[0.4rem] items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="#ABB2BF"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="#282C33"
            class="w-6 h-6"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75"
            />
          </svg>

          vinittiwari1912@gmail.com
        </span>
      </span>
    </span>
  </span>
</span>
