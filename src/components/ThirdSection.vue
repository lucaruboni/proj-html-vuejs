<script>
export default{
    name: 'ThirdSection'
}

</script>

<template>
            <div class="line position-absolute "></div>

    <div class="container">
        <div class="row pb-5">



            <div class="col-12 text-center pt-5 pb-5">
                <h6 class="text_primary">HOW IT WORKS IN PRACTICE</h6>
                        <h1 class="my-3"><span class="text_primary logo_scss">Logistical</span> Procedure</h1>
                        <p id="presentation_p">We work with innovative methodologies to ensure that entire delivery process is done from start to finish  as planned.</p>

            </div>
            <div class="col-2 me-4 d-flex flex-column gap-4 text-center">
                <div class="bg_primary my_border align-self-center d-flex justify-content-center">
                    <h3 class=" align-self-center text_primary">1</h3>
                </div>
                <h3>
                    Collection of information
                </h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur.
                </p>
            </div>
            <div class="col-2 me-4 d-flex flex-column gap-4 text-center">
                <div class="bg_primary my_border align-self-center d-flex justify-content-center">
                    <h3 class=" align-self-center text_primary">2</h3>
                </div>
                <h3>
                    Service Invoice Sending
                </h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur.
                </p>
            </div>
            <div class="col-2 me-4 d-flex flex-column gap-4 text-center">
                <div class="bg_primary my_border align-self-center d-flex justify-content-center">
                    <h3 class=" align-self-center text_primary">3</h3>
                </div>
                <h3>
                    Withdrawal of Cargo
                </h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur.
                </p>
            </div>
            <div class="col-2 me-4 d-flex flex-column gap-4 text-center">
                <div class="bg_primary my_border align-self-center d-flex justify-content-center">
                    <h3 class=" align-self-center text_primary">4</h3>
                </div>
                <h3>
                    Transport Customer Order
                </h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur.
                </p>
            </div>
            <div class="col-2 me-4 d-flex flex-column gap-4 text-center">
                <div class="bg_primary my_border align-self-center d-flex justify-content-center">
                    <h3 class=" align-self-center text_primary">5</h3>
                </div>
                <h3>
                    Succesful Delivery
                </h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur.
                </p>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use './scss/partials/variables.scss' as *;
.line{
    border-bottom: 5px solid $primary-transparent;
    top: 47.5%;
    left: 0;
    width: 100%;
    z-index: 1;
    
    

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
.my_border{
    width: 50px;
    height: 50px;
    justify-self: center;
    border-radius: 50%;
    background-color: $primary-transparent;
    z-index: 100;
}
    
</style>