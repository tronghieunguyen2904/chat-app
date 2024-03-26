<template>
    <button
        class="flex flex-row items-center hover:bg-gray-100 rounded-xl p-2">
        <div
        class="flex items-center justify-center h-8 w-8 bg-gray-200 rounded-full">
        M
        </div>
        <div class="ml-2 text-sm font-semibold"><slot name="name"></slot></div>
        <div
        class="flex items-center justify-center ml-auto text-xs text-white bg-red-500 h-4 w-4 rounded leading-none">
        <slot name="number_message"></slot>
        </div>
    </button>
</template>

  