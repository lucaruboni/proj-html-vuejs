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


                                                        <!-- THIRD SECTION -->

    <section class=" position-relative">

        <div class="line position-absolute top-50 "></div>

        <div class="container">
            <div class="row">

                

                <div class="col-12 text-center pt-5 pb-5">
                    <h6 class="text_primary">HOW IT WORKS IN PRACTICE</h6>
                            <h1 class="my-3"><span class="text_primary logo_scss">Logistical</span> Procedure</h1>
                            <p id="presentation_p">We work with innovative methodologies to ensure that entire delivery process is done from start to finish  as planned.</p>
                            
                </div>
                <div class="col-2 me-4 d-flex flex-column gap-4 text-center">
                    <h2>1</h2>
                    <h3>
                        Collection of information
                    </h3>
                    <p>
                        Lorem ipsum dolor sit amet consectetur.
                    </p>
                </div>
                <div class="col-2 me-4 d-flex flex-column gap-4 text-center">
                    <h2>1</h2>
                    <h3>
                        Collection of information
                    </h3>
                    <p>
                        Lorem ipsum dolor sit amet consectetur.
                    </p>
                </div>
                <div class="col-2 me-4 d-flex flex-column gap-4 text-center">
                    <h2>1</h2>
                    <h3>
                        Collection of information
                    </h3>
                    <p>
                        Lorem ipsum dolor sit amet consectetur.
                    </p>
                </div>
                <div class="col-2 me-4 d-flex flex-column gap-4 text-center">
                    <h2>1</h2>
                    <h3>
                        Collection of information
                    </h3>
                    <p>
                        Lorem ipsum dolor sit amet consectetur.
                    </p>
                </div>
                <div class="col-2 me-4 d-flex flex-column gap-4 text-center">
                    <h2>1</h2>
                    <h3>
                        Collection of information
                    </h3>
                    <p>
                        Lorem ipsum dolor sit amet consectetur.
                    </p>
                </div>
            </div>
        </div>
    </section>



                                                        <!-- /THIRD SECTION -->



</template>

<style lang="scss" scoped>
@use './scss/partials/variables.scss' as *;
  
  .bg_dark{
      background-color: $bg-primary;
  }





    
  .bg_dark{
      background-color: $bg-primary;
  }

  .bg_grey{
      background-color: $bg-grey;
  }

  .text_primary{
      color: $primary;
  }

  .bg_primary{
      background-color: $primary;
  }

  .bg_primary_transparent{
      background-color: $primary-transparent;
      border-radius: 50%;
      padding: 1rem;
  }
  .btn_border{
      border-color: $primary;
      border-radius: 3px;
  }

  .col-12{
    h6{
        font-weight: 700;
    }
    h1{
        font-size: 3.2rem;
        font-weight: 700;
        .logo_scss{
        background-color: $primary-transparent;
        padding-left: 8px;
        padding-right: 8px;
        padding-bottom: 3px;
        border-radius: 5px
    }
    }




    
  }

</style>