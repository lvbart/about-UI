<template>
  <form class="w-full max-w-sm">
    <div class="flex items-center border-b-2 border-teal-400 py-2">
      <input class="bg-transparent border-none w-full text-gray-400 mr-5 py-1 px-2 leading-tight focus: outline-none" type="text" placeholder="搜索内容">
      <button class="flex-shrink-0 bg-teal-400 hover:bg-teal-500 border-teal-300 hover:border-teal-600 text-sm border-4 text-white py-1 px-2 rounded" type="button">
        搜索
      </button>
      <button class="flex-shrink-0 border-transparent border-4 text-teal-500 hover:text-teal-800 text-sm py-1 px-2 rounded" type="button">
      取消
    </button>
    </div>
  </form>
</template>

<script>
export default {
  name: 'SearchBar',

}
</script>

<style>

</style>