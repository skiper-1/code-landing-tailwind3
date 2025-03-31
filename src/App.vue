<script setup>
import { CodeBracketSquareIcon } from '@heroicons/vue/24/solid';
</script>
<template>
  <header class="container flex items-center mx-auto my-2 gap-10">
    <a href="#" class="flex items-center gap-2">
      <CodeBracketSquareIcon class="size-12 text-indigo-500 -rotate-12" />
      <span class="font-extrabold text-2xl">Code Editor</span>
    </a>
    <nav class="grow">
      <ul class="flex items-center gap-6 font-medium">
        <li class="mr-auto">
          <a href="#" class="hover:text-indigo-500">Library</a>
        </li>
        <li>
          <a
            href="#"
            class="hover:bg-indigo-500 px-3 py-2 rounded-lg hover:text-white text-md"
            >Log In</a
          >
        </li>
        <li>
          <a
            href="#"
            class="hover:bg-indigo-500 px-3 py-2 hover:rounded-lg hover:text-white hover:text-md"
          >
            Sign In
          </a>
        </li>
      </ul>
    </nav>
  </header>
  <main class="container"></main>
</template>
