<template>
  <Navbar/>
  <ContactForm/>
</template>

<script>
import Navbar from "@/components/Navbar";
import ContactForm from "@/components/ContactForm";

export default {
  name: 'App',
  components: {
    Navbar,
    ContactForm
  }
}
</script>

<style>

</style>
