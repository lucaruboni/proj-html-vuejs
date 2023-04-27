<script>
import FirstSection from './FirstSection.vue'
import SecondSection from './SecondSection.vue'
import ThirdSection from './ThirdSection.vue'
import FourthSection from './FourthSection.vue'
import FifthSection from './FifthSection.vue'
export default{
    name: 'PageMain',
    components: {
        FirstSection,
        SecondSection,
        ThirdSection,
        FourthSection,
        FifthSection
    }
}

</script>

<template>
    <main>

                                                        <!-- FIRST SECTION -->

    <section>
        <FirstSection></FirstSection>
    </section>

                                                        <!-- /FIRST SECTION -->



                                                        <!-- SECOND SECTION -->

                                                        
    <section class="bg_dark">
        <SecondSection></SecondSection>
    </section>





                                                        <!-- /SECOND SECTION -->


                                                        <!-- THIRD SECTION -->

    <section class=" position-relative bg_alternative">
        <ThirdSection></ThirdSection>
    </section>



                                                        <!-- /THIRD SECTION -->

                                                        <!-- FOURTH SECTION -->
    <section class="bg_section pb-5">
        <FourthSection></FourthSection>
    </section>



                                                        <!-- /FOURTH SECTION -->

                                                        <!-- FIFTH SECTION -->
    <section class="bg_dark">
        <FifthSection></FifthSection>
    </section>

                                                        <!-- /FIFTH SECTION -->

</main>
   

</template>

<style lang="scss" scoped>
@use './scss/partials/variables.scss' as *;
  

  .bg_dark{
      background-color: $bg-primary;
  }
  .bg_alternative{
    background-color: $bg-alternative;
  }

  .bg_section{
    background-image: url(/img/bg-10.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: 20%;
  }






</style>