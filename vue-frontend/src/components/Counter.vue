<template>
  <div>
    <p>I'm a Counter!</p>
    <p>Count: {{count}}</p>
    <button v-on:click="count+=1">Increment</button>
    <button v-on:click="count-=1">Decrement</button>
  </div>
</template>

<script>
export default {
  props : {
    initial_count: Number,
  },
  data() {
    return {
      count: this.initial_count 
    };
  }
};
</script>

<style>
</style>

