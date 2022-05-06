<template>
  <HomeTemplate />
</template>

<script lang="ts">
import Vue from 'vue'
import { books } from '@/store'

export default Vue.extend({
  layout: 'ibook',
  asyncData() {
    debugger
    console.log(books.books[0].title)
  }
})
</script>
