<template>
  <div>
    <h1 class="item">Hello world!</h1>
    <block></block>
    <content-list></content-list>
  </div>
</template>

<script>
import Block from './Block.vue'
import ContentList from './ContestList.vue'

export default {
  components: {
    Block,
    ContentList
  }
}
</script>

<style>
.item {
  color: red;
}
</style>
