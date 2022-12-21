<template>
  <Navbar/>
  <ContactForm/>
  <About/>
  <Feedback/>
  <Footer/>
</template>

<script>
import Navbar from "@/components/Navbar";
import ContactForm from "@/components/ContactForm";
import About from "@/components/About";
import Feedback from "@/components/Feedback";
import Footer from "@/components/Footer";

export default {
  name: 'App',
  components: {
    Navbar,
    ContactForm,
    About,
    Feedback,
    Footer
  }
}
</script>

<style>

</style>
