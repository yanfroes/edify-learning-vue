<template>
  <div>
    <NavOne />
    <PageHeader title="Our People" />
    <Teachers />
    <Footer />
  </div>
</template>
<script>
  import PageHeader from "../components/PageHeader";
  import NavOne from "../components/NavThree";
  import Footer from "../components/Footer";
  import Teachers from "../components/Teachers";
  export default {
    components: {Teachers, Footer, NavOne, PageHeader},
    head(){
      return {
        title: "Edify Online | Teachers"
      }
    }
  }
</script>
