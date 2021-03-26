<template>
  <div>
    <NavThree />
    <BannerThree />
    <CourseCatThree />
    <Testimonial />
    <ClientsLogoOne />
    <CallToActionFive />
    <Footer />
  </div>
</template>
<script>
  import NavThree from "../components/NavThree";
  import Footer from "../components/Footer";
  import BannerThree from "../components/BannerThree";
  import CourseCatThree from "../components/CourseCatThree";
  import Testimonial from "../components/Testimonial";
  import ClientsLogoOne from "../components/ClientsLogoOne";
  import CallToActionFive from "../components/CallToActionFive";

  export default {
    components: {
      Footer,
      NavThree,
      BannerThree,
      CourseCatThree,
      Testimonial,
      ClientsLogoOne,
      CallToActionFive,

    },
    head(){
      return{
        title: "Edify Online - Exchange"
      }
    }
  }
</script>
