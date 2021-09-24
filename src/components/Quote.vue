<template>
  <div class="md:flex bg-gray-100 rounded-xl p-8 md:p-0 md:max-w-2xl overflow-hidden">
    <img class="w-32 h-32 md:w-48 md:h-auto md:rounded-none rounded-full mx-auto" src="../assets/sarah-dayan.jpg" alt="" width="384" height="512">
    <div class="pt-6 md:p-8 text-center md:text-left space-y-4">
      <blockquote>
        <p class="text-lg font-semibold">
          “Tailwind CSS is the only framework that I've seen scale
          on large teams. It’s easy to customize, adapts to any design,
          and the build size is tiny.”
        </p>
      </blockquote>
      <div class="font-medium">
        <div class="text-blue-500">
          Sarah Dayan
        </div>
        <div class="text-gray-500">
          Staff Engineer, Algolia
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Quote"
}
</script>

<style scoped>

</style>