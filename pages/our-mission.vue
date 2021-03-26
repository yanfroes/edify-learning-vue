<template>
  <div>
    <NavThree />
    <PageHeader title="Our Mission" />
    <OurMission />
    <Footer />
  </div>
</template>
<script>
  import PageHeader from "../components/PageHeader";
  import NavThree from "../components/NavThree";
  import Footer from "../components/Footer";
  import OurMission from "../components/OurMission";
  export default {
    components: {OurMission, Footer, NavThree, PageHeader},
    head(){
      return {
        title: "Edify | About Us"
      }
    }
  }
</script>
