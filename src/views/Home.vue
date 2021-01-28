<template>
  <div class="home">
    <SectionOne />
    <SectionTwo/>
    <SectionThree/>
    <Section-Four/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import SectionOne from "../views/SectionOne.vue";
import SectionTwo from './SectionTwo.vue';
import SectionThree from './SectionThree.vue';
import SectionFour from './SectionFour.vue';

export default {
  name: "Home",
  components: {
    HelloWorld,
    SectionOne,
    SectionTwo,
    SectionThree,
    SectionFour,
  },
};
</script>

,
    SectionFour<style>
</style>
