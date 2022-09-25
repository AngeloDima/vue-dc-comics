<template>
  <div id="app">
   <header_one />
   <main_one />
   <footer_one />
   <footer_profondo />
  </div>
</template>

<script>
import header_one from '/src/assets/header_one.vue';
import main_one from '/src/assets/main_one.vue';
import footer_one from '/src/assets/footer_one.vue';
import footer_profondo from '/src/assets/footer_profondo.vue';

export default {
  name: 'App',
  components: {
    header_one,
    main_one,
    footer_one,
    footer_profondo,
},
}
</script>
  


<style lang="scss" scoped>

</style>
