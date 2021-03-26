<template>
  <div>
    <NavOne />
    <PageHeader title="Anil P. Agarwal" />
    <Anil />
    <Footer />
  </div>
</template>
<script>
  import PageHeader from "../components/PageHeader";
  import NavOne from "../components/NavThree";
  import Footer from "../components/Footer";
  import Anil from "../components/Anil";
  export default {
    components: {Anil, Footer, NavOne, PageHeader},
    head(){
      return {
        title: "Edify Online | Our People"
      }
    }
  }
</script>
