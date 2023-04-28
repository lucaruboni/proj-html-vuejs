<script>

export default{
    name: 'SixthSection',
    props: {
        address: String,
        cell_number: String,
        email: String
    },

}

</script>

<template>
        <div class="container">
            <div class="row">
                <div class="col-8 my-5">
                    <div class="text_area mt-3">
                        <h6 class="text_primary pt-3">SEND A MESSAGE</h6>
                                <h1 class="py-3">Get in <span class="bg_primary_transparent_square text_primary">Touch</span></h1>
                                <p id="presentation_p">We will respond to your message as soon as possible</p>
                    </div>


                                                <!-- FORM -->

                    <div class="row g-3">
                      <div class="col p-2">
                        <input type="text" class="form-control bg_grey" placeholder="First name" aria-label="First name">
                      </div>
                      <div class="col p-2">
                        <input type="text" class="form-control bg_grey" placeholder="Email" aria-label="Last name">
                      </div>
                      
                    </div>
                    
                    <div class="row g-3">

                      <div class="col p-2">
                        <input type="text" class="form-control bg_grey" placeholder="Phone" aria-label="First name">
                      </div>

                      <div class="col p-2">
                        <select id="inputState" class="form-select bg_grey">
                          <option selected></option>
                          <option>...</option>
                        </select>

                      </div>

                      <div class="form-floating">
                        <textarea class="form-control bg_grey"  id="floatingTextarea2" style="height: 100px;"></textarea>
                        <label for="floatingTextarea2"></label>
                      </div>
                      
                    </div>
                    
                    <button class="bg_btn py-2 px-4 rounded-2 text-light">SEND</button>
                            
                </div>


                                                    <!-- /FORM -->


                <div class="col-4 my-5">
                    <div class="text_area mt-3">
                       
                                <h1 class="py-3">Example Inc.</h1>
                                <p class="text_dark">Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
                                <p class="text_dark">Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>

                                
                                    <div class="icon_row d-flex gap-3 p-3 text_primary">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="60" height="60" fill="currentColor" class="bi bi-telephone-fill bg_primary_transparent" viewBox="0 0 16 16">
                                        <path fill-rule="evenodd" d="M1.885.511a1.745 1.745 0 0 1 2.61.163L6.29 2.98c.329.423.445.974.315 1.494l-.547 2.19a.678.678 0 0 0 .178.643l2.457 2.457a.678.678 0 0 0 .644.178l2.189-.547a1.745 1.745 0 0 1 1.494.315l2.306 1.794c.829.645.905 1.87.163 2.611l-1.034 1.034c-.74.74-1.846 1.065-2.877.702a18.634 18.634 0 0 1-7.01-4.42 18.634 18.634 0 0 1-4.42-7.009c-.362-1.03-.037-2.137.703-2.877L1.885.511z"/>
                                        </svg>
                                        <span class="align-self-center">
                                            {{ cell_number }}
                                        </span>
                                    
                                    </div>
        
                                    <div class="icon_row d-flex gap-3 p-3 text_primary">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="60" height="60" fill="currentColor" class="bi bi-envelope-fill bg_primary_transparent" viewBox="0 0 16 16">
                                          <path d="M.05 3.555A2 2 0 0 1 2 2h12a2 2 0 0 1 1.95 1.555L8 8.414.05 3.555ZM0 4.697v7.104l5.803-3.558L0 4.697ZM6.761 8.83l-6.57 4.027A2 2 0 0 0 2 14h12a2 2 0 0 0 1.808-1.144l-6.57-4.027L8 9.586l-1.239-.757Zm3.436-.586L16 11.801V4.697l-5.803 3.546Z"/>
                                        </svg>
                                        <span class="align-self-center">
                                            {{ email }}
                                        </span>

                                    </div>

                                    <div class="icon_row d-flex gap-3 p-3 text_primary">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="60" height="60" fill="currentColor" class="bi bi-geo-alt-fill bg_primary_transparent" viewBox="0 0 16 16">
                                          <path d="M8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10zm0-7a3 3 0 1 1 0-6 3 3 0 0 1 0 6z"/>
                                        </svg>
                                        <span class="align-self-center">
                                            {{ address }}
                                        </span>
                                    </div>

                                    <button class="btn btn_border text_primary">VIEW MAP</button>

                                    
                    </div>
                </div>

                                                       

            </div>
        </div>
</template>

<style lang="scss" scoped>

@use './scss/partials/variables.scss' as *;
  .bg_primary_transparent_square{
      background-color: $primary-transparent;
      border-radius: 5px;
      padding: 10px;
  }

  .bg_primary_transparent{
      background-color: $primary-transparent;
      border-radius: 50%;
      padding: 1rem;
  }
  .text_primary{
      color: $primary;
  }


  .text_area{
     h1{
        font-size: 3rem;
        font-weight: 700
     }
  }

  .bg_grey{
    background-color: $text-dark-bg;
  }

 .bg_btn{
    background-color: $primary;
    border-color: $primary;
    font-size: 1.2rem;
    font-weight: 600;
    margin-top: 1rem;
    
 }

 .text_dark{
    color: $text-dark;
    
 }
 .btn_border{
        border-color: $primary;
    }
</style>