<template>
  <div class="h-full w-full">
    <nav class="flex w-full items-center justify-between bg-sb-gray text-white">
      <div>
        <div class="block sm:hidden">menu mobile</div>
        <p class="ml-4 text-xl font-medium text-white">The Sandbox</p>
      </div>
      <div class="flex justify-center gap-2">
        <!-- LANG -->
        <div
          class="my-2 flex cursor-pointer items-center gap-2 rounded-md px-2 text-gray-400 transition-colors hover:bg-gray-700 hover:text-white"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-5 w-5"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
            stroke-width="2"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"
            />
          </svg>
          <span class="text-sm">EN</span>
        </div>
        <!-- CRYPTO -->
        <div
          class="flex flex-col items-start gap-0.5 border-x border-gray-500 py-2 px-3"
        >
          <span class="text-[11px] text-gray-400">MAINNET NETWORK</span>
          <div class="flex items-center justify-center gap-2 text-sm">
            <div class="flex items-center justify-start gap-1 font-medium">
              <img src="/matic.webp" alt="matic" class="h-3.5 w-3.5" />
              <span>94 MATIC</span>
            </div>
            <div
              class="flex cursor-pointer items-center justify-start gap-1 transition-transform hover:scale-105 hover:transform-gpu"
            >
              <img src="/sand.webp" alt="sand" class="h-3.5 w-3.5" />
              <span class="font-medium text-purple-500">1460 SAND</span>
            </div>
          </div>
        </div>
        <!-- USER -->
        <div class="group relative flex cursor-pointer">
          <div
            class="absolute -right-3 top-1.5 rounded-sm bg-sky-400 py-0.5 px-1 text-[8px] group-hover:animate-bounce"
          >
            NEW
          </div>
          <img
            src="/guille.png"
            alt="Perfil"
            class="my-auto mx-1 h-10 w-10 rounded-full border-2 border-sky-400 group-hover:border-sky-300"
          />
        </div>
        <!-- CART -->
        <div class="flex border-l border-gray-500">
          <div
            class="m-2 flex cursor-pointer items-center rounded-md px-3 text-gray-400 transition-colors hover:bg-gray-700 hover:text-white"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-5 w-5"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              stroke-width="2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z"
              />
            </svg>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>
