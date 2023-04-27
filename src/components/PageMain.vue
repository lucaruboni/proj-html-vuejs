<script>
import FirstSection from './FirstSection.vue'
import SecondSection from './SecondSection.vue'
export default{
    name: 'PageMain',
    components: {
        FirstSection,
        SecondSection
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



</template>

<style lang="scss" scoped>
@use './scss/partials/variables.scss' as *;
  
  .bg_dark{
      background-color: $bg-primary;
  }

</style>