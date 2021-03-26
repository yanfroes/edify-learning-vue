<template>
  <div>
    <NavThree />
    <BannerThree />
    <AboutTwo />
    <CallToActionTwo />
    <PricingPage />
    <CourseCatThree />
    <Faq />
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
  import AboutTwo from "../components/AboutTwo";
  import CallToActionTwo from "../components/CallToActionTwo";
  import PricingPage from "../components/PricingPage";
  import Faq from "../components/Faq";
  import Testimonial from "../components/Testimonial";
  import ClientsLogoOne from "../components/ClientsLogoOne";
  import CallToActionFive from "../components/CallToActionFive";

  export default {
    components: {
      Footer,
      NavThree,
      BannerThree,
      CourseCatThree,
      AboutTwo,
      CallToActionTwo,
      PricingPage,
      Faq,
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
