<template>
  <Block></Block>
  <ContentList></ContentList>
</template>

<script>
import Block from './Block.vue'
import ContentList from './ContestList.vue'


export default {
  
  components: {
    Block, ContentList
  }
}
</script>

<style>
.item {
  color: red;
}
</style>
