<template>
  <div id="app">
   <header_one />
   <main_one />
   <footer_one />
  </div>
</template>

<script>
import header_one from '/src/assets/header_one.vue';
import main_one from '/src/assets/main_one.vue';
import footer_one from '/src/assets/footer_one.vue';

export default {
  name: 'App',
  components: {
    header_one,
    main_one,
    footer_one,
},
}
</script>
  


<style>

</style>
