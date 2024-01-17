<template>
  <h1 class="item">Hello world!</h1>

  <h2>{{ test }}</h2>

  <h2 :id="id">{{ a }}</h2>

  <h2 :class="bool ? 'y' : 'n'">{{ bool ? 'yes' : 'no' }}</h2>

  <p v-if="1 === 1">
    Condition elem
  </p>
  <p v-else-if="1 == 1">
    else if
  </p>
  <p v-else>
    Else
  </p>
</template>

<script>
  const a = 100

export default {
  data() {
    return {
      test: 'ITHub',
      id: 'elem_value',
      bool: true,
      a
    }
  }
}
</script>

<style>
.block {
  color: purple;
}
</style>
