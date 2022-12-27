<template>
  <transition appear appear-active-class="fade-enter-active">
    <div>
      <Navbar/>
      <ContactForm/>
      <CallMe class="d-md-none"/>
      <About/>
      <Benefits/>
      <HowItWorks/>
      <Feedback/>
      <Footer/>

    </div>
  </transition>

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
import SuccessPopUp from "@/components/SuccessPopUp";

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
    CallMe,
    SuccessPopUp
  },
  data: () => ({
    showSuccessPopUp: false
  })
}
</script>

<style>

</style>
