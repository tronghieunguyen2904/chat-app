<template>
                <div class="select-none" role="listitem">
                  <button
                    aria-label="conversation withElijah Sabrina"
                    tabindex="0"
                    class="w-full h-[5.75rem] px-5 py-6 mb-3 flex rounded focus:bg-indigo-50 dark:active:bg-gray-600 dark:focus:bg-gray-600 dark:hover:bg-gray-600 hover:bg-indigo-50 active:bg-indigo-100 focus:outline-none transition duration-500 ease-out"
                  >
                    <div class="mr-4">
                      <div
                        class="w-7 h-7 rounded-full bg-cover bg-center"
                        style="
                          background-image: url('https://images.unsplash.com/photo-1539571696357-5a69c17a67c6?ixlib=rb-1.2.1&amp;ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;auto=format&amp;fit=crop&amp;w=387&amp;q=80');
                        "
                      ></div>
                    </div>
                    <div class="w-full flex flex-col">
                      <div class="w-full">
                        <div class="flex items-start">
                          <div class="grow mb-4 text-start">
                            <p
                              class="outline-none text-sm text-black opacity-60 dark:text-white dark:opacity-70 font-semibold leading-4 tracking-[.01rem]"
                            >
                              <slot name="name"></slot>
                            </p>
                          </div>
                          <p
                            class="outline-none text-xs text-black opacity-60 dark:text-white dark:opacity-70 font-light leading-4 tracking-[.01rem]"
                          >
                            6:20 pm
                          </p>
                        </div>
                      </div>
                      <div class="flex justify-between items-center">
                        <div class="flex justify-between w-full">
                          <p
                            class="outline-none text-sm text-black opacity-60 dark:text-white dark:opacity-70 font-normal leading-4 tracking-[.01rem] flex justify-start items-center">
                            <span class="line-clamp-1 text-start">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Commodi veritatis pariatur quae distinctio doloribus ut magnam alias, voluptatibus, ipsa aliquid delectus beatae ullam ex laborum est dolorum minima nobis quisquam?</span>
                          </p>                         
                          <div
                            class="flex items-center justify-center ml-auto text-xs text-white px-2 bg-red-500 h-4 w-4 rounded leading-none">
                            <slot name="number_message"></slot>
                          </div>
                        </div>
                        <!---->
                      </div>
                    </div>
                  </button>
                </div>
</template>
