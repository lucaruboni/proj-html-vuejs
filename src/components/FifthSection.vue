<script>
export default{
    name: 'FifthSection'
}
</script>

<template>
        <div class="container">
            <div class="row">
               
                    <div class="col-12 text-light text-center">
                            <h6 class="text_primary">CUSTOMER TESTIMONIALS</h6>
                            <h1 class="p-3">Trusted <span class="bg_primary_transparent_square">Feedback</span></h1>
                            <p id="presentation_p">We work intensively in search of ideals that can add up in the lives of our customers. This is what moves us and we are grateful for the recognition.</p>
                            
                                
                                
                            
                    </div>      
                   
            </div>
            <div class="row row-cols-4 justify-content-between pb-5">
                <div class="col bg_grey p-4 rounded-4">
                    <div class="icon_row p-3">
                        <img src="/img/logo-1.png" alt="">

                    </div>

                    <div class="text-area text-light p-3 d-flex flex-column gap-4">
                        
                        <p class="my_text">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. In dolor, officiis similique impedit nisi laborum numquam soluta? Pariatur, distinctio! Voluptas dicta consequuntur, excepturi provident architecto perferendis veniam animi aspernatur quae quos quaerat quasi id velit ducimus suscipit perspiciatis ab culpa.
                        </p>
                    </div>
                </div>
                <div class="col bg_grey p-4 rounded-4">
                    <div class="icon_row p-3">
                        <img src="/img/logo-2.png" alt="">

                    </div>

                    <div class="text-area text-light p-3 d-flex flex-column gap-4">
                        
                        <p class="my_text">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. In dolor, officiis similique impedit nisi laborum numquam soluta? Pariatur, distinctio! Voluptas dicta consequuntur, excepturi provident architecto perferendis veniam animi aspernatur quae quos quaerat quasi id velit ducimus suscipit perspiciatis ab culpa.
                        </p>
                    </div>
                </div>
                <div class="col bg_grey p-4 rounded-4">
                    <div class="icon_row p-3">
                        <img src="/img/logo-3.png" alt="">

                    </div>

                    <div class="text-area text-light p-3 d-flex flex-column gap-4">
                        
                        <p class="my_text">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. In dolor, officiis similique impedit nisi laborum numquam soluta? Pariatur, distinctio! Voluptas dicta consequuntur, excepturi provident architecto perferendis veniam animi aspernatur quae quos quaerat quasi id velit ducimus suscipit perspiciatis ab culpa.
                        </p>
                    </div>
                </div>
            </div>
        </div>
</template>

<style lang="scss" scoped>
@use './scss/partials/variables.scss' as *;
  
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
  .bg_primary_transparent_square{
      background-color: $primary-transparent;
      border-radius: 5px;
      padding: 10px;
  }
  .btn_border{
      border-color: $primary;
      border-radius: 3px;
  }

  .icon_row{
      color: $primary;
  }

  .col-12{
      margin-top: 100px;
      margin-bottom: 40px;
      h1{
        font-weight: 700;
        font-size: 3rem;
      }
  }

  .my_text{
    color: $text-dark;
  }


</style>