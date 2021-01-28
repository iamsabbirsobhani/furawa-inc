<template>
  <div class="about">
    <h1>This is an about page</h1>
    <Contact>
      <h2>Our Beloved</h2>
      <Employee/>
    </Contact>
  </div>
</template>

<script>
import Contact from './Contact.vue'
import Employee from './Employee.vue'
export default {
  components:{ Contact, Employee }
}
</script>

<style>
.about h1{
  margin: 0;
}

</style>