<template lang="pug">
h3.text-green-700.text-center Vue vite template

p Features:
ul
  li windicss
  li
    | Icons
    |
    i-iconoir:bicycle.align-middle
  li pug
  li prettier + eslint (opinionated strict rules)
  li typescript
  Test
</template>


<style>
body {
  @apply bg-dark-700 text-gray-300 p-3 text-xl;
}

h3 {
  @apply text-3xl font-bold;
}

li {
  @apply ml-8 list-disc;
}
</style>
