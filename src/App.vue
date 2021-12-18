<template>
  <div class="container">
    <category-list />
  </div>
</template>
<script lang="ts">
import { defineComponent } from 'vue'
import CategoryList from './CategoryList.vue'
export default defineComponent({
  components: {
    CategoryList
  }
})

</script>
<style lang="scss">
  .container {
    box-sizing: border-box;
    overflow-y: scroll;
    max-width: 320px;
    margin-left: auto;
    margin-right: auto;
    -webkit-box-shadow: 4px 10px 16px -5px rgba(0,0,0,0.75);
    -moz-box-shadow: 4px 10px 16px -5px rgba(0,0,0,0.75);
    box-shadow: 4px 10px 16px -5px rgba(0,0,0,0.75);
  }
</style>
