<template>
  <div class="w-full rounded shadow-2xl overflow-hidden md:grid grid-cols-2 max-w-3xl">
    <!--    BEGIN header-->
    <div class="bg-white dark:bg-gray-800 px-6 py-8 space-y-4 md:col-span-2 md:px-8 transition-all">
      <h1 class="text-2xl font-semibold text-teal dark:text-white">
        Join our community
      </h1>
      <h2 class="text-lime font-semibold">
        30-day, hassle-free money back guarantee
      </h2>
      <p class="text-gray-400 leading-7">
        Gain access to our full library of tutorials along with expert code reviews. Perfect for any developers who are
        serious about honing their skills.
      </p>
    </div>
    <!--    END Header-->
    <!--    BEGIN call to action section-->
    <div class="px-6 py-8 bg-teal text-white space-y-4 md:px-8">
      <h2 class="text-xl font font-semibold">Monthly Subscription</h2>
      <p class="flex items-center">
        <strong class="text-3xl">$29</strong>
        <span class="opacity-70 font-light ml-2">per month</span>
      </p>
      <p>
        Full access for less than $1 a day
      </p>
      <div class="pt-4">
        <button class="bg-lime h-14 w-full rounded-md text-xl font-semibold shadow-xl hover:opacity-90">
          Sign Up
        </button>
      </div>
    </div>
    <!--    END call to action section-->
    <!--    BEGIN footer section-->
    <div class="px-6 py-8 bg-tealLight text-white space-y-4 md:px-8">
      <h2 class="text-xl font font-semibold">Why us</h2>
      <ul class="text-gray-200">
        <li>Tutorials by industry expert</li>
        <li>Peer & expert code review</li>
        <li>Coding exercises</li>
        <li>Access to our GitHub repos</li>
        <li>Community forum</li>
        <li>Flashcard decks</li>
        <li>New videos every week</li>
      </ul>
    </div>
    <!--    END footer section-->
  </div>
</template>

<script>
export default {
  name: "Example"
}
</script>

<style scoped>

</style>