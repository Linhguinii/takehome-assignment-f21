<template>
  <!-- PART 4: Add your code here -->
  <div>
    <p>{{name}}</p>
    <Counter v-bind:initial_count="1"/>
  </div>
</template>

<script>
import Counter from "./Counter.vue";
// PART 4: Add your code here
export default {
  components: {
    Counter,
  },
  data(){
    return{
      id : "none",
      name: "Show",
      episodes_seen: 1
    };
  }
};
</script>

<style>
</style>
