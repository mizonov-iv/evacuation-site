<template>
  <Navbar/>
  <ContactForm/>
  <About/>
  <Benefits/>
  <HowItWorks/>
  <Feedback/>
  <CallMe/>
  <Footer/>
</template>

<script>
import Navbar from "@/components/Navbar";
import ContactForm from "@/components/ContactForm";
import About from "@/components/About";
import Feedback from "@/components/Feedback";
import Footer from "@/components/Footer";
import Benefits from "@/components/Benefits";
import HowItWorks from "@/components/HowItWorks";
import CallMe from "@/components/CallMe.vue";

export default {
  name: 'App',
  components: {
    Navbar,
    ContactForm,
    About,
    Feedback,
    Footer,
    Benefits,
    HowItWorks,
    CallMe
  }
}
</script>

<style>

</style>
