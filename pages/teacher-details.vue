<template>
  <div>
    <NavOne />
    <PageHeader title="Anil P. Agarwal" />
    <TeacherDetails />
    <Footer />
  </div>
</template>
<script>
  import PageHeader from "../components/PageHeader";
  import NavOne from "../components/NavThree";
  import Footer from "../components/Footer";
  import TeacherDetails from "../components/TeacherDetails";
  export default {
    components: {TeacherDetails, Footer, NavOne, PageHeader},
    head(){
      return {
        title: "Edify Online | Our People"
      }
    }
  }
</script>
