<script>
import FirstSection from './FirstSection.vue'
import SecondSection from './SecondSection.vue'
import ThirdSection from './ThirdSection.vue'
export default{
    name: 'PageMain',
    components: {
        FirstSection,
        SecondSection,
        ThirdSection
    }
}

</script>

<template>

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
    <section class="bg_section">

    </section>



                                                        <!-- /FOURTH SECTION -->



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
    height: 700px;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: 20%;
  }



    



</style>