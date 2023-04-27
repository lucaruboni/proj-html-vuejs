<script>
export default{
    name: 'FourtSection'
}

</script>

<template>
   <div class="container">
            <div class="row justify-content-evenly">
                <div class="col-12 mt-5 mb-5 text-light text-center">
                            <h6 class="text_primary mb-4">WHAT ARE WE DOING</h6>
                            <h1><span class=" logo_scss">Results</span> in Numbers</h1>
                            <p id="presentation_p">With all of this expertise and capability comes an unrivalled commitment to customer service. We will work hard to understand your needs in order to develop a productive, long-term partnership.</p>
                </div>   

                <div class="col-2 me-4 d-flex flex-column gap-4 text-center text-light mb-5 mt-5">
                    
                    <h2 class="text_primary">
                        128
                    </h2>
                    <h3>    
                        Certifications
                    </h3>
                </div>

                <div class="col-2 me-4 d-flex flex-column gap-4 text-center text-light mt-5">
                    
                    <h2 class="text_primary">
                        230
                    </h2>
                    <h3>    
                        Employees
                    </h3>

                </div>

                <div class="col-2 me-4 d-flex flex-column gap-4 text-center text-light mt-5">
                    
                    <h2 class="text_primary">
                        517
                    </h2>
                    <h3>    
                        Customers
                    </h3>

                </div>

                <div class="col-2 me-4 d-flex flex-column gap-4 text-center text-light mt-5">
                    
                    <h2 class="text_primary">
                        94
                    </h2>
                    <h3>    
                        Country Served
                    </h3>

                </div>
            </div>
        </div>
</template>

<style lang="scss" scoped>
@use './scss/partials/variables.scss' as *;
  .text_primary{
      color: $primary;
  }
    .logo_scss{
        background-color: $primary-transparent;
        padding-left: 8px;
        padding-right: 8px;
        padding-bottom: 3px;
        border-radius: 5px;
        
    }

.col-12{
    h1{
        font-weight: 700;
        font-size: 3rem;
    }
}
    
.col-2{
    h3{
        font-size: 1.3rem;
    }
    h2{
        font-size: 2.8rem;
        font-weight: 600;
    }
}

</style>