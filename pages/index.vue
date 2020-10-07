<template>
  <div class="container">
    <div>
      <Counter></Counter>
      <Counter></Counter>
      <Counter></Counter>
    </div>
  </div>
</template>

<script>
import Counter from '~/components/Counter.vue'
export default {
  components: {
    Counter
  }
}
</script>
