<template>
<div class="flex flex-col items-center">
  <span class="text-3xl sm:text-5xl text-purple-400 font-extrabold tracking-widest">{{japaneseText}}</span>
  <h1 class="text-3xl sm:text-5xl dark:text-gray-50 font-semibold capitalize mt-4 mb-8">{{text}}</h1>
</div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
export default defineComponent({
  name: 'SectionTitle',
  props: {
    text: String,
    japaneseText: String
  }
})
</script>
