<script>
import AppTitle from './components/AppTitle.vue';

export default {
  components: {
    AppTitle
  },
}
</script>


<template>
  <div class="my_title">
    <AppTitle></AppTitle>
  </div>
</template>


<style>
  .my_title {
    height: 95vh;

    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
</style>