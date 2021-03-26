<template>
  <div>
    <NavOne />
    <PageHeader title="Contact" />
    <Contact />
    <Footer />
  </div>
</template>
<script>
  import PageHeader from "../components/PageHeader";
  import NavOne from "../components/NavThree";
  import Footer from "../components/Footer";
  import Contact from "../components/Contact";
  export default {
    components: {Contact, Footer, NavOne, PageHeader},
    head(){
      return {
        title: "Edify Online | Contact"
      }
    }
  }
</script>
