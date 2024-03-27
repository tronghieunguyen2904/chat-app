<template>
  <div class="w-full min-h-[5.25rem] px-8 pt-9">
    <div class="w-full flex justify-center items-center">
      <div class="group mr-4 md:hidden">
        <button
          class="group flex justify-center items-center outline-none rounded-full focus:outline-none transition-all duration-200 focus:bg-gray-50 hover:bg-gray-50 dark:hover:bg-gray-700 dark:focus:bg-gray-600 w-7 h-7"
          title="close conversation"
          aria-label="close conversation">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            aria-hidden="true"
            class="w-[1.25rem] h-[1.25rem] text-gray-300 group-hover:text-indigo-300">
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M15.75 19.5L8.25 12l7.5-7.5"></path>
          </svg>
        </button>
      </div>
      <div class="flex grow">
        <button class="mr-5 outline-none" aria-label="profile avatar">
          <div
            class="w-[2.25rem] h-[2.25rem] rounded-full bg-cover bg-center"
            style="
              background-image: url('https://images.unsplash.com/photo-1522556189639-b150ed9c4330?ixlib=rb-1.2.1&amp;ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;auto=format&amp;fit=crop&amp;w=387&amp;q=80');"></div>
        </button>
        <div class="flex flex-col">
          <p
            class="outline-none text-sm text-black opacity-60 dark:text-white dark:opacity-70 font-semibold leading-4 tracking-[.01rem] mb-2 default-outline cursor-pointer"
            tabindex="0">
            Dylan Billy
          </p>
          <p
            class="outline-none text-sm text-black opacity-60 dark:text-white dark:opacity-70 leading-4 tracking-[.01rem] font-extralight default-outline rounded-[.25rem]"
            tabindex="0"
            aria-label="Last seen december 16, 2019">
            Last seen Dec 16, 2019
          </p>
        </div>
      </div>
      <div class="flex">
        <button
          class="group flex justify-center items-center outline-none rounded-full focus:outline-none transition-all duration-200 focus:bg-gray-50 hover:bg-gray-50 dark:hover:bg-gray-700 dark:focus:bg-gray-600 group w-7 h-7 mr-3"
          title="search messages"
          aria-label="search messages">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            aria-hidden="true"
            class="w-[1.25rem] h-[1.25rem] text-gray-400 group-hover:text-indigo-300">
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z"
            ></path>
          </svg>
        </button>
        <div class="dropdown dropdown-bottom dropdown-end ml-1">
            <button id="dropdownMenuIconButton" tabindex="0" role="button"  class="inline-flex self-center items-center p-2 text-sm font-medium text-center text-gray-900 " type="button">
                <svg class="w-4 h-4 text-gray-500 dark:text-gray-400" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 4 15">
                    <path d="M3.5 1.5a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0Zm0 6.041a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0Zm0 5.959a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0Z"/>
                </svg>
            </button>
            <ul tabindex="0" class="dropdown-content z-[1] menu p-2 shadow bg-base-100 rounded-box w-52">
                <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white">Reply</a>
                </li>
                <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white">Forward</a>
                </li>
                <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white">Copy</a>
                </li>
                <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white">Report</a>
                </li>
                <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white">Delete</a>
                </li>
            </ul>
        </div>
      </div>
    </div>
  </div>
</template>
