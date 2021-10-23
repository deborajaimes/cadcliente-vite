<template>
  <button
    class="
      px-6
      py-2
      transition
      ease-in
      duration-200
      uppercase
      rounded-full
      hover:bg-gray-800 hover:text-white
      border-2 border-gray-900
      focus:outline-none
    "
  >
    <span>
      <slot></slot>
    </span>
  </button>
</template>

<script>
export default {};
</script>

<style>
</style>