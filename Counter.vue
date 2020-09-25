<template>
  <div>
  <p>I'm a Counter!</p>
  <button v-on:click="count++"> {{ count }} times.</button>
  <button v-on:click="count--"> {{ count }} times.</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      count: 0
    };
  },

};
</script>

<style>
</style>

