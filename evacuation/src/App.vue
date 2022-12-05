<template>
  <Navbar/>
  <ContactForm/>
  <About/>
</template>

<script>
import Navbar from "@/components/Navbar";
import ContactForm from "@/components/ContactForm";
import About from "@/components/About";

export default {
  name: 'App',
  components: {
    Navbar,
    ContactForm,
    About
  }
}
</script>

<style>

</style>
