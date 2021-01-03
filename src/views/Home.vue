<template>
  <div>
      <h1>Welcome to Countdown Timer</h1>
      <Counter
        :year="2022"
        :month="0"
        :day="8"
        :hour="1"
        :minute="16"
        :second="0"
      ></Counter>
  </div>
</template>

<script>
import Counter from '../components/Counter.vue'
export default {
    components: {
        Counter
    }
}
</script>

<style>

</style>