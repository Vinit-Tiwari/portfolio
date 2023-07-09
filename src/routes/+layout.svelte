<script>
  import { onMount } from "svelte";
  import "../app.postcss";
  import { page } from "$app/stores";
  import PageTransition from "../lib/components/PageTransition.svelte";
  let menuSelected = false;
</script>

<span class="flex flex-col w-full h-full p-0 m-0 h-full">
  <span class="flex bg-[#282C33] w-full h-full p-0 m-0 h-full">
    <span
      class="hidden lg:flex fixed p-[1rem] flex-col items-center gap-[0.8rem]"
    >
      <span class="w-[0.1rem] h-[7rem] bg-[#ABB2BF]" />

      <a target="_blank" href="https://github.com/Vinit-Tiwari">
        <svg
          width="21"
          height="20"
          viewBox="0 0 21 20"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M10.5 0C4.69875 0 0 4.58819 0 10.2529C0 14.7899 3.00562 18.6219 7.17937 19.9804C7.70437 20.0701 7.90125 19.7625 7.90125 19.4934C7.90125 19.2499 7.88813 18.4425 7.88813 17.5838C5.25 18.058 4.5675 16.9558 4.3575 16.3791C4.23938 16.0843 3.7275 15.1743 3.28125 14.9308C2.91375 14.7386 2.38875 14.2644 3.26813 14.2516C4.095 14.2388 4.68563 14.9949 4.8825 15.3025C5.8275 16.8533 7.33688 16.4175 7.94063 16.1484C8.0325 15.4819 8.30812 15.0334 8.61 14.777C6.27375 14.5207 3.8325 13.6364 3.8325 9.71466C3.8325 8.59965 4.23938 7.67689 4.90875 6.95918C4.80375 6.70286 4.43625 5.65193 5.01375 4.24215C5.01375 4.24215 5.89313 3.97301 7.90125 5.29308C8.74125 5.06239 9.63375 4.94704 10.5263 4.94704C11.4188 4.94704 12.3113 5.06239 13.1513 5.29308C15.1594 3.9602 16.0387 4.24215 16.0387 4.24215C16.6163 5.65193 16.2488 6.70286 16.1438 6.95918C16.8131 7.67689 17.22 8.58684 17.22 9.71466C17.22 13.6492 14.7656 14.5207 12.4294 14.777C12.81 15.0975 13.1381 15.7126 13.1381 16.6738C13.1381 18.0452 13.125 19.1474 13.125 19.4934C13.125 19.7625 13.3219 20.0829 13.8469 19.9804C15.9314 19.2935 17.7428 17.9854 19.026 16.2403C20.3092 14.4953 20.9996 12.4012 21 10.2529C21 4.58819 16.3013 0 10.5 0Z"
            fill="#ABB2BF"
          />
        </svg>
      </a>

      <a target="_blank" href="mailto: vinittiwari1912@gmail.com">
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
      </a>

      <a href="https://www.linkedin.com/in/vinit-tiwari1912">
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
      </a>
    </span>

    <span class="flex flex-col w-full">
      <nav class="w-full fixed bg-[#282C33] z-50">
        <span
          class="flex m-auto text-white items-center justify-between max-w-[90rem] p-[1rem] text-[18px]"
        >
          <a href="/" class="flex items-center text-[20px] gap-[0.4rem]">
            <svg
              width="16"
              height="17"
              viewBox="0 0 16 17"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M12 0.5H8V4.5H4H0V8.5V12.5V16.5H4H8V12.5H12H16V8.5V4.5V0.5H12ZM4 12.5H8V8.5H12V4.5H8V8.5H4V12.5Z"
                fill="white"
              />
            </svg>
            Vinit
          </a>

          <span
            class="md:flex lg:flex hidden w-full items-center max-w-[30rem] justify-evenly"
          >
            <a href="/" class="flex cursor-pointer">
              <p class="text-[#C778DD]">#</p>
              home
            </a>

            <a href="/projects" class="flex cursor-pointer">
              <p class="text-[#C778DD]">#</p>
              works
            </a>

            <a href="/about-me" class="flex cursor-pointer">
              <p class="text-[#C778DD]">#</p>
              about-me
            </a>

            <a href="/contacts" class="flex cursor-pointer">
              <p class="text-[#C778DD]">#</p>
              contacts
            </a>
          </span>

          {#if menuSelected == false}
            <span
              on:click={() => (menuSelected = true)}
              class="flex md:hidden lg:hidden cursor-pointer"
            >
              <svg
                width="24"
                height="24"
                viewBox="0 0 24 24"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <rect y="5" width="24" height="2" fill="#D9D9D9" />
                <rect x="9" y="12" width="15" height="2" fill="#D9D9D9" />
              </svg>
            </span>
          {:else}
            <span
              on:click={() => (menuSelected = false)}
              class="flex md:hidden lg:hidden z-60 cursor-pointer"
            >
              <svg
                width="24"
                height="24"
                viewBox="0 0 24 24"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <rect
                  width="1"
                  height="1"
                  transform="matrix(1 0 0 -1 11 12)"
                  fill="#D9D9D9"
                />
                <rect
                  x="3"
                  y="19.9706"
                  width="24"
                  height="2"
                  transform="rotate(-45 3 19.9706)"
                  fill="#D9D9D9"
                />
                <rect
                  x="4"
                  y="3"
                  width="24"
                  height="2"
                  transform="rotate(45 4 3)"
                  fill="#D9D9D9"
                />
              </svg>
            </span>
          {/if}
        </span>
      </nav>

      {#if menuSelected == true}
        <span
          class="flex flex-col text-[22px] p-[1rem] pb-[5rem] justify-between text-white z-60 bg-[#282C33] absolute top-0 left-0 w-[100vw] h-[100vh] gap-[1rem] pt-[5rem]"
        >
          <span class="flex gap-[1rem] flex-col">
            <a
              href="/"
              on:click={() => (menuSelected = false)}
              class="flex cursor-pointer"
            >
              <p class="text-[#C778DD]">#</p>
              home
            </a>

            <a
              href="/projects"
              on:click={() => (menuSelected = false)}
              class="flex cursor-pointer"
            >
              <p class="text-[#C778DD]">#</p>
              works
            </a>

            <a
              href="/about-me"
              on:click={() => (menuSelected = false)}
              class="flex cursor-pointer"
            >
              <p class="text-[#C778DD]">#</p>
              about-me
            </a>

            <a
              href="/contacts"
              on:click={() => (menuSelected = false)}
              class="flex cursor-pointer"
            >
              <p class="text-[#C778DD]">#</p>
              contacts
            </a>
          </span>

          <span class="flex items-center justify-center h-max gap-[1rem]">
            <a target="_blank" href="https://github.com/Vinit-Tiwari">
              <svg
                width="21"
                height="20"
                viewBox="0 0 21 20"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M10.5 0C4.69875 0 0 4.58819 0 10.2529C0 14.7899 3.00562 18.6219 7.17937 19.9804C7.70437 20.0701 7.90125 19.7625 7.90125 19.4934C7.90125 19.2499 7.88813 18.4425 7.88813 17.5838C5.25 18.058 4.5675 16.9558 4.3575 16.3791C4.23938 16.0843 3.7275 15.1743 3.28125 14.9308C2.91375 14.7386 2.38875 14.2644 3.26813 14.2516C4.095 14.2388 4.68563 14.9949 4.8825 15.3025C5.8275 16.8533 7.33688 16.4175 7.94063 16.1484C8.0325 15.4819 8.30812 15.0334 8.61 14.777C6.27375 14.5207 3.8325 13.6364 3.8325 9.71466C3.8325 8.59965 4.23938 7.67689 4.90875 6.95918C4.80375 6.70286 4.43625 5.65193 5.01375 4.24215C5.01375 4.24215 5.89313 3.97301 7.90125 5.29308C8.74125 5.06239 9.63375 4.94704 10.5263 4.94704C11.4188 4.94704 12.3113 5.06239 13.1513 5.29308C15.1594 3.9602 16.0387 4.24215 16.0387 4.24215C16.6163 5.65193 16.2488 6.70286 16.1438 6.95918C16.8131 7.67689 17.22 8.58684 17.22 9.71466C17.22 13.6492 14.7656 14.5207 12.4294 14.777C12.81 15.0975 13.1381 15.7126 13.1381 16.6738C13.1381 18.0452 13.125 19.1474 13.125 19.4934C13.125 19.7625 13.3219 20.0829 13.8469 19.9804C15.9314 19.2935 17.7428 17.9854 19.026 16.2403C20.3092 14.4953 20.9996 12.4012 21 10.2529C21 4.58819 16.3013 0 10.5 0Z"
                  fill="#ABB2BF"
                />
              </svg>
            </a>

            <a target="_blank" href="mailto: vinittiwari1912@gmail.com">
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
            </a>

            <a
              target="_blank"
              href="https://www.linkedin.com/in/vinit-tiwari1912"
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
            </a>
          </span>
        </span>
      {:else}
        <PageTransition url={$page.url}>
          <slot />
        </PageTransition>
      {/if}
    </span>
  </span>

  <!-- FOOTER -->
  <span class="flex gap-[1rem] border-t text-white flex-col p-[1rem]">
    <span class="flex w-full items-center justify-around">
      <span>
        <span class="flex items-center text-[20px] gap-[0.4rem]">
          <svg
            width="16"
            height="17"
            viewBox="0 0 16 17"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M12 0.5H8V4.5H4H0V8.5V12.5V16.5H4H8V12.5H12H16V8.5V4.5V0.5H12ZM4 12.5H8V8.5H12V4.5H8V8.5H4V12.5Z"
              fill="white"
            />
          </svg>
          Vinit
        </span>

        <p class="text-[#ABB2BF]">Web designer and full-stack developer</p>
      </span>

      <span class="flex flex-col gap-[1rem]">
        <p class="text-[19px]">Media</p>

        <span class="flex gap-[1rem]">
          <a target="_blank" href="https://github.com/Vinit-Tiwari">
            <svg
              width="21"
              height="20"
              viewBox="0 0 21 20"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M10.5 0C4.69875 0 0 4.58819 0 10.2529C0 14.7899 3.00562 18.6219 7.17937 19.9804C7.70437 20.0701 7.90125 19.7625 7.90125 19.4934C7.90125 19.2499 7.88813 18.4425 7.88813 17.5838C5.25 18.058 4.5675 16.9558 4.3575 16.3791C4.23938 16.0843 3.7275 15.1743 3.28125 14.9308C2.91375 14.7386 2.38875 14.2644 3.26813 14.2516C4.095 14.2388 4.68563 14.9949 4.8825 15.3025C5.8275 16.8533 7.33688 16.4175 7.94063 16.1484C8.0325 15.4819 8.30812 15.0334 8.61 14.777C6.27375 14.5207 3.8325 13.6364 3.8325 9.71466C3.8325 8.59965 4.23938 7.67689 4.90875 6.95918C4.80375 6.70286 4.43625 5.65193 5.01375 4.24215C5.01375 4.24215 5.89313 3.97301 7.90125 5.29308C8.74125 5.06239 9.63375 4.94704 10.5263 4.94704C11.4188 4.94704 12.3113 5.06239 13.1513 5.29308C15.1594 3.9602 16.0387 4.24215 16.0387 4.24215C16.6163 5.65193 16.2488 6.70286 16.1438 6.95918C16.8131 7.67689 17.22 8.58684 17.22 9.71466C17.22 13.6492 14.7656 14.5207 12.4294 14.777C12.81 15.0975 13.1381 15.7126 13.1381 16.6738C13.1381 18.0452 13.125 19.1474 13.125 19.4934C13.125 19.7625 13.3219 20.0829 13.8469 19.9804C15.9314 19.2935 17.7428 17.9854 19.026 16.2403C20.3092 14.4953 20.9996 12.4012 21 10.2529C21 4.58819 16.3013 0 10.5 0Z"
                fill="#ABB2BF"
              />
            </svg>
          </a>

          <a target="_blank" href="mailto: vinittiwari1912@gmail.com">
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
          </a>

          <a
            target="_blank"
            href="https://www.linkedin.com/in/vinit-tiwari1912"
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
          </a>
        </span>
      </span>
    </span>
  </span>
</span>
