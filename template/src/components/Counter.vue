<template>
  <div class="counter-wrapper">
    <div class="counter">\{{count}}</div>
    <button @click="$store.commit('INCREMENT')">+</button>
    <button @click="$store.commit('DECREMENT')">-</button>
  </div>
</template>

<script>
'use strict'

export default {
  computed: {
    count() {
      return this.$store.state.count
    }
  }
}
</script>

<style>
.counter {
  cursor: pointer;
  margin: 100px auto;
  border-radius: 30px;
  width: 200px;
  height: 200px;
  text-align: center;
  line-height: 200px;
  font-size: 5rem;
  background-color: #f0f0f0;
  user-select: none;
}
</style>
