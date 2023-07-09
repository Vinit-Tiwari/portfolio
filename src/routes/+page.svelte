<script>
  import Card from "../lib/components/Card.svelte";
  import projectData from "$lib/ProjectData.js";
  import { fade, slide } from "svelte/transition";
</script>

<span class="text-white flex pt-[4rem] pb-[1rem] flex-col">
  <span
    class="flex flex-col lg:flex-row m-auto p-[2rem] max-w-[70rem] items-center justify-center"
  >
    <span class="flex flex-col h-full gap-[2rem] items-start">
      <span class="flex gap-[0.3rem] flex-wrap text-[35px] font-medium" in:fade>
        Vinit is a
        <p class="text-[#C778DD] h-min">full-stack</p>
        <p class="text-[#C778DD] h-min">developer</p>
        and
        <p class="text-[#C778DD] h-min">web</p>
        <p class="text-[#C778DD] h-min">designer</p>
      </span>
      <span class="text-[#ABB2BF] text-[20px] max-w-[30rem]">
        He crafts responsive websites where technologies meet creativity
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
        <span class="text-[18px]"> Currently working on Portfolio </span>
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

        With great power comes great electricity bill
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
        >- Dr. Who</span
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
            I'm a self-taught full-stack developer based in Maharashtra, India.
            I can develop responsive websites from scratch and raise them into
            modern user-friendly web experiences.
          </p>
          <p class="text-[#ABB2BF]">
            Transforming my creativity and knowledge into a websites has been my
            passion for over 3 year. I have been helping various clients to
            establish their presence online. I always strive to learn about the
            newest technologies and frameworks.
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

        <span class="text-[#ABB2BF] flex gap-[0.4rem] items-center">
          <svg
            width="21px"
            height="21px"
            viewBox="0 -28.5 256 256"
            version="1.1"
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            preserveAspectRatio="xMidYMid"
          >
            <g>
              <path
                d="M216.856339,16.5966031 C200.285002,8.84328665 182.566144,3.2084988 164.041564,0 C161.766523,4.11318106 159.108624,9.64549908 157.276099,14.0464379 C137.583995,11.0849896 118.072967,11.0849896 98.7430163,14.0464379 C96.9108417,9.64549908 94.1925838,4.11318106 91.8971895,0 C73.3526068,3.2084988 55.6133949,8.86399117 39.0420583,16.6376612 C5.61752293,67.146514 -3.4433191,116.400813 1.08711069,164.955721 C23.2560196,181.510915 44.7403634,191.567697 65.8621325,198.148576 C71.0772151,190.971126 75.7283628,183.341335 79.7352139,175.300261 C72.104019,172.400575 64.7949724,168.822202 57.8887866,164.667963 C59.7209612,163.310589 61.5131304,161.891452 63.2445898,160.431257 C105.36741,180.133187 151.134928,180.133187 192.754523,160.431257 C194.506336,161.891452 196.298154,163.310589 198.110326,164.667963 C191.183787,168.842556 183.854737,172.420929 176.223542,175.320965 C180.230393,183.341335 184.861538,190.991831 190.096624,198.16893 C211.238746,191.588051 232.743023,181.531619 254.911949,164.955721 C260.227747,108.668201 245.831087,59.8662432 216.856339,16.5966031 Z M85.4738752,135.09489 C72.8290281,135.09489 62.4592217,123.290155 62.4592217,108.914901 C62.4592217,94.5396472 72.607595,82.7145587 85.4738752,82.7145587 C98.3405064,82.7145587 108.709962,94.5189427 108.488529,108.914901 C108.508531,123.290155 98.3405064,135.09489 85.4738752,135.09489 Z M170.525237,135.09489 C157.88039,135.09489 147.510584,123.290155 147.510584,108.914901 C147.510584,94.5396472 157.658606,82.7145587 170.525237,82.7145587 C183.391518,82.7145587 193.761324,94.5189427 193.539891,108.914901 C193.539891,123.290155 183.391518,135.09489 170.525237,135.09489 Z"
                fill="#ABB2BF"
                fill-rule="nonzero"
              />
            </g>
          </svg>

          xyzqw
        </span>

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
