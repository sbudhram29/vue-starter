<template>
  <div class="home">
    <Hero msg="Welcome to Vuejs"></Hero>
    <HelloWorld msg="Lorem Ipsum is simply dummy text of the printing and
     typesetting industry." ></HelloWorld>
  </div>
</template>

<script>
// @ is an alias to /src
import Hero from '@/components/Hero.vue';
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'home',
  components: {
    Hero,
    HelloWorld,
  },
};
</script>
