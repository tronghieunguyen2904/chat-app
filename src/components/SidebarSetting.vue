<template>
  <div
    class="xs:w-full md:w-11 md:h-full md:py-7 xs:py-5 px-5 flex xs:flex-row md:flex-col items-center transition-all duration-500 xs:order-1 md:-order-none"
  >
    <div class="grow">
      <nav aria-label="Main navigation">
        <ul class="xs:flex md:block xs:justify-between xs:items-center">
          <li>
            <div class="xs:mb-0 md:mb-6">
              <button
                class="group relative focus:outline-none"
                title="Conversations"
                aria-label="Conversations"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  fill="currentColor"
                  aria-hidden="true"
                  class="w-7 h-6 group-focus:text-indigo-400 hover:text-indigo-400 active:text-indigo-400 active:scale-110 dark:text-gray-500 transition ease-out duration-200 text-indigo-400 dark:text-indigo-400"
                >
                  <path
                    fill-rule="evenodd"
                    d="M5.337 21.718a6.707 6.707 0 01-.533-.074.75.75 0 01-.44-1.223 3.73 3.73 0 00.814-1.686c.023-.115-.022-.317-.254-.543C3.274 16.587 2.25 14.41 2.25 12c0-5.03 4.428-9 9.75-9s9.75 3.97 9.75 9c0 5.03-4.428 9-9.75 9-.833 0-1.643-.097-2.417-.279a6.721 6.721 0 01-4.246.997z"
                    clip-rule="evenodd"
                  ></path></svg
                ><!---->
              </button>
            </div>
          </li>
          <li>
            <div class="xs:mb-0 md:mb-6">
              <button
                class="group relative focus:outline-none"
                title="Contacts"
                aria-label="Contacts"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  fill="currentColor"
                  aria-hidden="true"
                  class="w-7 h-6 group-focus:text-indigo-400 hover:text-indigo-400 active:text-indigo-400 active:scale-110 dark:text-gray-500 transition ease-out duration-200 text-gray-300"
                >
                  <path
                    fill-rule="evenodd"
                    d="M7.5 6a4.5 4.5 0 119 0 4.5 4.5 0 01-9 0zM3.751 20.105a8.25 8.25 0 0116.498 0 .75.75 0 01-.437.695A18.683 18.683 0 0112 22.5c-2.786 0-5.433-.608-7.812-1.7a.75.75 0 01-.437-.695z"
                    clip-rule="evenodd"
                  ></path></svg
                ><!---->
              </button>
            </div>
          </li>
          <li>
            <div
              class="relative xs:block md:hidden"
              aria-labelledby="small-profile-menu-button"
            >
              <button
                id="small-profile-menu-button"
                class="bg-white rounded-full active:scale-110 focus:outline-none focus:scale-110 transition duration-200 ease-out"
                aria-expanded="false"
                aria-controls="profile-menu"
                aria-label="toggle profile menu"
                style="
                  box-shadow: rgba(193, 202, 255, 0.5) 0px 0.125rem 0.3125rem,
                    rgba(193, 202, 255, 0.5) 0.125rem 0px 0.3125rem,
                    rgba(193, 202, 255, 0.5) -0.125rem 0px 0.3125rem,
                    rgba(193, 202, 255, 0.5) 0px -0.125rem 0.3125rem;
                "
              >
                <div
                  id="user-avatar"
                  class="w-7 h-7 rounded-full bg-cover bg-center"
                  style="
                    background-image: url('https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&amp;ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;auto=format&amp;fit=crop&amp;w=387&amp;q=80');
                  "
                ></div>
              </button>
              <div
                id="small-profile-menu-dropdown"
                aria-labelledby="small-profile-menu-button"
              >
                <!---->
                <div
                  data-v-5a116fd1=""
                  class="md:bottom-0 md:left-[2.5rem] md:top-[auto] bottom-[3.125rem] left-[-4.8125rem] absolute z-[100] w-[12.5rem] mt-2 rounded-sm bg-white dark:bg-gray-800 shadow-lg border border-gray-100 dark:border-gray-600 focus:outline-none"
                  role="menu"
                  aria-orientation="vertical"
                  aria-labelledby="menu-button"
                  tabindex="-1"
                  style="display: none"
                >
                  <div role="none">
                    <button
                      aria-label="Profile Information"
                      class="w-full px-4 py-3 flex items-center border-b opacity-60 dark:opacity-70 outline-none text-sm border-gray-200 dark:border-gray-600 transition-all duration-200 text-black dark:text-white active:bg-gray-100 dark:hover:bg-gray-600 dark:focus:bg-gray-600 hover:bg-gray-50"
                      role="menuitem"
                      tabindex="0"
                    >
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        fill="none"
                        viewBox="0 0 24 24"
                        stroke-width="1.5"
                        stroke="currentColor"
                        aria-hidden="true"
                        class="h-5 w-5 mr-3 text-black opacity-60 dark:text-white dark:opacity-70"
                      >
                        <path
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          d="M11.25 11.25l.041-.02a.75.75 0 011.063.852l-.708 2.836a.75.75 0 001.063.853l.041-.021M21 12a9 9 0 11-18 0 9 9 0 0118 0zm-9-3.75h.008v.008H12V8.25z"
                        ></path>
                      </svg>
                      Profile Information</button
                    ><button
                      aria-label="Password Change"
                      class="w-full px-4 py-3 flex items-center border-b opacity-60 dark:opacity-70 outline-none text-sm border-gray-200 dark:border-gray-600 transition-all duration-200 text-black dark:text-white active:bg-gray-100 dark:hover:bg-gray-600 dark:focus:bg-gray-600 hover:bg-gray-50"
                      role="menuitem"
                    >
                      <a
                        href="/reset/"
                        class="w-full flex items-center justify-start"
                        ><svg
                          xmlns="http://www.w3.org/2000/svg"
                          fill="none"
                          viewBox="0 0 24 24"
                          stroke-width="1.5"
                          stroke="currentColor"
                          aria-hidden="true"
                          class="h-5 w-5 mr-3 text-black opacity-60 dark:text-white dark:opacity-70"
                        >
                          <path
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            d="M16.023 9.348h4.992v-.001M2.985 19.644v-4.992m0 0h4.992m-4.993 0l3.181 3.183a8.25 8.25 0 0013.803-3.7M4.031 9.865a8.25 8.25 0 0113.803-3.7l3.181 3.182m0-4.991v4.99"
                          ></path>
                        </svg>
                        Password Change
                      </a></button
                    ><button
                      aria-label="Logout"
                      class="w-full px-4 py-3 flex items-center border-b opacity-60 dark:opacity-70 outline-none text-sm border-gray-200 dark:border-gray-600 transition-all duration-200 text-red-500 dark:hover:text-red-50 hover:bg-red-50 active:bg-red-100 dark:hover:bg-red-900"
                      role="menuitem"
                    >
                      <a
                        href="/access/sign-in/"
                        class="w-full flex items-center justify-start"
                        ><svg
                          xmlns="http://www.w3.org/2000/svg"
                          fill="none"
                          viewBox="0 0 24 24"
                          stroke-width="1.5"
                          stroke="currentColor"
                          aria-hidden="true"
                          class="h-5 w-5 mr-3"
                        >
                          <path
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            d="M15.75 9V5.25A2.25 2.25 0 0013.5 3h-6a2.25 2.25 0 00-2.25 2.25v13.5A2.25 2.25 0 007.5 21h6a2.25 2.25 0 002.25-2.25V15M12 9l-3 3m0 0l3 3m-3-3h12.75"
                          ></path>
                        </svg>
                        Logout
                      </a>
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </li>
          <li class="xs:hidden md:inline">
            <div class="xs:mb-0 md:mb-6">
              <button
                class="group relative focus:outline-none"
                title="Notifications"
                aria-label="Notifications 3 new notifications"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  fill="currentColor"
                  aria-hidden="true"
                  class="w-7 h-6 group-focus:text-indigo-400 hover:text-indigo-400 active:text-indigo-400 active:scale-110 dark:text-gray-500 transition ease-out duration-200 text-gray-300"
                >
                  <path
                    fill-rule="evenodd"
                    d="M5.25 9a6.75 6.75 0 0113.5 0v.75c0 2.123.8 4.057 2.118 5.52a.75.75 0 01-.297 1.206c-1.544.57-3.16.99-4.831 1.243a3.75 3.75 0 11-7.48 0 24.585 24.585 0 01-4.831-1.244.75.75 0 01-.298-1.205A8.217 8.217 0 005.25 9.75V9zm4.502 8.9a2.25 2.25 0 104.496 0 25.057 25.057 0 01-4.496 0z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
                <div
                  class="absolute right-0 top-3 w-5 h-5 flex items-center justify-center outline-none bg-indigo-400 text-xs text-white border border-white dark:border-gray-800 rounded-full transition duration-500"
                >
                  3
                </div>
              </button>
            </div>
          </li>
          <li>
            <div class="xs:mb-0 md:mb-6">
              <button
                class="group relative focus:outline-none"
                title="Call log"
                aria-label="Call log"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  fill="currentColor"
                  aria-hidden="true"
                  class="w-7 h-6 group-focus:text-indigo-400 hover:text-indigo-400 active:text-indigo-400 active:scale-110 dark:text-gray-500 transition ease-out duration-200 text-gray-300"
                >
                  <path
                    fill-rule="evenodd"
                    d="M1.5 4.5a3 3 0 013-3h1.372c.86 0 1.61.586 1.819 1.42l1.105 4.423a1.875 1.875 0 01-.694 1.955l-1.293.97c-.135.101-.164.249-.126.352a11.285 11.285 0 006.697 6.697c.103.038.25.009.352-.126l.97-1.293a1.875 1.875 0 011.955-.694l4.423 1.105c.834.209 1.42.959 1.42 1.82V19.5a3 3 0 01-3 3h-2.25C8.552 22.5 1.5 15.448 1.5 6.75V4.5z"
                    clip-rule="evenodd"
                  ></path></svg
                ><!---->
              </button>
            </div>
          </li>
          <li class="xs:inline md:hidden">
            <div class="xs:mb-0 md:mb-6">
              <button
                class="group relative focus:outline-none"
                title="Settings"
                aria-label="Settings"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  fill="currentColor"
                  aria-hidden="true"
                  class="w-7 h-6 group-focus:text-indigo-400 hover:text-indigo-400 active:text-indigo-400 active:scale-110 dark:text-gray-500 transition ease-out duration-200 text-gray-300"
                >
                  <path
                    fill-rule="evenodd"
                    d="M11.078 2.25c-.917 0-1.699.663-1.85 1.567L9.05 4.889c-.02.12-.115.26-.297.348a7.493 7.493 0 00-.986.57c-.166.115-.334.126-.45.083L6.3 5.508a1.875 1.875 0 00-2.282.819l-.922 1.597a1.875 1.875 0 00.432 2.385l.84.692c.095.078.17.229.154.43a7.598 7.598 0 000 1.139c.015.2-.059.352-.153.43l-.841.692a1.875 1.875 0 00-.432 2.385l.922 1.597a1.875 1.875 0 002.282.818l1.019-.382c.115-.043.283-.031.45.082.312.214.641.405.985.57.182.088.277.228.297.35l.178 1.071c.151.904.933 1.567 1.85 1.567h1.844c.916 0 1.699-.663 1.85-1.567l.178-1.072c.02-.12.114-.26.297-.349.344-.165.673-.356.985-.57.167-.114.335-.125.45-.082l1.02.382a1.875 1.875 0 002.28-.819l.923-1.597a1.875 1.875 0 00-.432-2.385l-.84-.692c-.095-.078-.17-.229-.154-.43a7.614 7.614 0 000-1.139c-.016-.2.059-.352.153-.43l.84-.692c.708-.582.891-1.59.433-2.385l-.922-1.597a1.875 1.875 0 00-2.282-.818l-1.02.382c-.114.043-.282.031-.449-.083a7.49 7.49 0 00-.985-.57c-.183-.087-.277-.227-.297-.348l-.179-1.072a1.875 1.875 0 00-1.85-1.567h-1.843zM12 15.75a3.75 3.75 0 100-7.5 3.75 3.75 0 000 7.5z"
                    clip-rule="evenodd"
                  ></path></svg
                ><!---->
              </button>
            </div>
          </li>
        </ul>
      </nav>
    </div>
    <div>
      <nav aria-label="Extra navigation" class="xs:hidden md:block">
        <ul>
          <li>
            <div class="xs:mb-0 md:mb-6">
              <button
                class="group relative focus:outline-none"
                title="Night mode"
                aria-label="Night mode"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  fill="currentColor"
                  aria-hidden="true"
                  class="w-7 h-6 group-focus:text-indigo-400 hover:text-indigo-400 active:text-indigo-400 active:scale-110 dark:text-gray-500 transition ease-out duration-200 text-gray-300"
                >
                  <path
                    fill-rule="evenodd"
                    d="M9.528 1.718a.75.75 0 01.162.819A8.97 8.97 0 009 6a9 9 0 009 9 8.97 8.97 0 003.463-.69.75.75 0 01.981.98 10.503 10.503 0 01-9.694 6.46c-5.799 0-10.5-4.701-10.5-10.5 0-4.368 2.667-8.112 6.46-9.694a.75.75 0 01.818.162z"
                    clip-rule="evenodd"
                  ></path></svg
                ><!---->
              </button>
            </div>
          </li>
          <li>
            <div class="xs:mb-0 md:mb-6">
              <button
                class="group relative focus:outline-none"
                title="Settings"
                aria-label="Settings"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  fill="currentColor"
                  aria-hidden="true"
                  class="w-7 h-6 group-focus:text-indigo-400 hover:text-indigo-400 active:text-indigo-400 active:scale-110 dark:text-gray-500 transition ease-out duration-200 text-gray-300"
                >
                  <path
                    fill-rule="evenodd"
                    d="M11.078 2.25c-.917 0-1.699.663-1.85 1.567L9.05 4.889c-.02.12-.115.26-.297.348a7.493 7.493 0 00-.986.57c-.166.115-.334.126-.45.083L6.3 5.508a1.875 1.875 0 00-2.282.819l-.922 1.597a1.875 1.875 0 00.432 2.385l.84.692c.095.078.17.229.154.43a7.598 7.598 0 000 1.139c.015.2-.059.352-.153.43l-.841.692a1.875 1.875 0 00-.432 2.385l.922 1.597a1.875 1.875 0 002.282.818l1.019-.382c.115-.043.283-.031.45.082.312.214.641.405.985.57.182.088.277.228.297.35l.178 1.071c.151.904.933 1.567 1.85 1.567h1.844c.916 0 1.699-.663 1.85-1.567l.178-1.072c.02-.12.114-.26.297-.349.344-.165.673-.356.985-.57.167-.114.335-.125.45-.082l1.02.382a1.875 1.875 0 002.28-.819l.923-1.597a1.875 1.875 0 00-.432-2.385l-.84-.692c-.095-.078-.17-.229-.154-.43a7.614 7.614 0 000-1.139c-.016-.2.059-.352.153-.43l.84-.692c.708-.582.891-1.59.433-2.385l-.922-1.597a1.875 1.875 0 00-2.282-.818l-1.02.382c-.114.043-.282.031-.449-.083a7.49 7.49 0 00-.985-.57c-.183-.087-.277-.227-.297-.348l-.179-1.072a1.875 1.875 0 00-1.85-1.567h-1.843zM12 15.75a3.75 3.75 0 100-7.5 3.75 3.75 0 000 7.5z"
                    clip-rule="evenodd"
                  ></path></svg
                ><!---->
              </button>
            </div>
          </li>
        </ul>
      </nav>
      <hr
        class="xs:hidden md:block mb-6 border-gray-100 dark:border-gray-600"
      />
      <div
        class="relative xs:hidden md:block"
        aria-labelledby="profile-menu-button"
      >
        <button
          id="profile-menu-button"
          class="bg-white rounded-full active:scale-110 focus:outline-none focus:scale-110 transition duration-200 ease-out"
          aria-expanded="false"
          aria-controls="profile-menu"
          aria-label="toggle profile menu"
          style="
            box-shadow: rgba(193, 202, 255, 0.5) 0px 0.125rem 0.3125rem,
              rgba(193, 202, 255, 0.5) 0.125rem 0px 0.3125rem,
              rgba(193, 202, 255, 0.5) -0.125rem 0px 0.3125rem,
              rgba(193, 202, 255, 0.5) 0px -0.125rem 0.3125rem;
          "
        >
          <div
            id="user-avatar"
            class="w-7 h-7 rounded-full bg-cover bg-center"
            style="
              background-image: url('https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&amp;ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;auto=format&amp;fit=crop&amp;w=387&amp;q=80');
            "
          ></div>
        </button>
        <div id="profile-menu-dropdown" aria-labelledby="profile-menu-button">
          <!---->
          <div
            data-v-5a116fd1=""
            class="md:bottom-0 md:left-[2.5rem] md:top-[auto] bottom-[3.125rem] left-[-4.8125rem] absolute z-[100] w-[12.5rem] mt-2 rounded-sm bg-white dark:bg-gray-800 shadow-lg border border-gray-100 dark:border-gray-600 focus:outline-none"
            role="menu"
            aria-orientation="vertical"
            aria-labelledby="menu-button"
            tabindex="-1"
            style="display: none"
          >
            <div role="none">
              <button
                aria-label="Profile Information"
                class="w-full px-4 py-3 flex items-center border-b opacity-60 dark:opacity-70 outline-none text-sm border-gray-200 dark:border-gray-600 transition-all duration-200 text-black dark:text-white active:bg-gray-100 dark:hover:bg-gray-600 dark:focus:bg-gray-600 hover:bg-gray-50"
                role="menuitem"
                tabindex="0"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke-width="1.5"
                  stroke="currentColor"
                  aria-hidden="true"
                  class="h-5 w-5 mr-3 text-black opacity-60 dark:text-white dark:opacity-70"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M11.25 11.25l.041-.02a.75.75 0 011.063.852l-.708 2.836a.75.75 0 001.063.853l.041-.021M21 12a9 9 0 11-18 0 9 9 0 0118 0zm-9-3.75h.008v.008H12V8.25z"
                  ></path>
                </svg>
                Profile Information</button
              ><button
                aria-label="Password Change"
                class="w-full px-4 py-3 flex items-center border-b opacity-60 dark:opacity-70 outline-none text-sm border-gray-200 dark:border-gray-600 transition-all duration-200 text-black dark:text-white active:bg-gray-100 dark:hover:bg-gray-600 dark:focus:bg-gray-600 hover:bg-gray-50"
                role="menuitem"
              >
                <a href="/reset/" class="w-full flex items-center justify-start"
                  ><svg
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke-width="1.5"
                    stroke="currentColor"
                    aria-hidden="true"
                    class="h-5 w-5 mr-3 text-black opacity-60 dark:text-white dark:opacity-70"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M16.023 9.348h4.992v-.001M2.985 19.644v-4.992m0 0h4.992m-4.993 0l3.181 3.183a8.25 8.25 0 0013.803-3.7M4.031 9.865a8.25 8.25 0 0113.803-3.7l3.181 3.182m0-4.991v4.99"
                    ></path>
                  </svg>
                  Password Change
                </a></button
              ><button
                aria-label="Logout"
                class="w-full px-4 py-3 flex items-center border-b opacity-60 dark:opacity-70 outline-none text-sm border-gray-200 dark:border-gray-600 transition-all duration-200 text-red-500 dark:hover:text-red-50 hover:bg-red-50 active:bg-red-100 dark:hover:bg-red-900"
                role="menuitem"
              >
                <a
                  href="/access/sign-in/"
                  class="w-full flex items-center justify-start"
                  ><svg
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke-width="1.5"
                    stroke="currentColor"
                    aria-hidden="true"
                    class="h-5 w-5 mr-3"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M15.75 9V5.25A2.25 2.25 0 0013.5 3h-6a2.25 2.25 0 00-2.25 2.25v13.5A2.25 2.25 0 007.5 21h6a2.25 2.25 0 002.25-2.25V15M12 9l-3 3m0 0l3 3m-3-3h12.75"
                    ></path>
                  </svg>
                  Logout
                </a>
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
