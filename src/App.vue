<script>
import Example from "./components/Example.vue";
import {Switch} from "@headlessui/vue";
import {ref} from "vue";
export default {
  components: {
    Example,
    Switch
  },
  setup() {
    const enabled = ref(false)

    return {
      enabled,
    }
  },
}
</script>

<template>
  <div :class="{dark:enabled}">
    <div class="flex flex-col justify-center gap-12 items-center p-6 min-h-screen bg-blue-100 dark:bg-gray-400 transition-all" >
      <Switch v-model="enabled" :class="[enabled ? 'bg-teal' : 'bg-gray-200', 'relative inline-flex flex-shrink-0 h-6 w-11 border-2 border-transparent rounded-full cursor-pointer transition-colors ease-in-out duration-200 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-teal']">
        <span class="sr-only">Use setting</span>
        <span aria-hidden="true" :class="[enabled ? 'translate-x-5' : 'translate-x-0', 'pointer-events-none inline-block h-5 w-5 rounded-full bg-white shadow transform ring-0 transition ease-in-out duration-200']" />
      </Switch>
      <Example/>
    </div>
  </div>
</template>

<style>
</style>
