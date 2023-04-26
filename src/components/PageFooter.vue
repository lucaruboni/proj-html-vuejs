<script>
import infos from './data/nexgen_header.json';
export default{
    name: 'PageFooter',
    props:{
        open_hours: String,
        cell_number: String,
        email: String,
        address: String,
        about: Array,
        transport: Array,
        support: Array
    },
    data(){
        return{
            infos: infos
        }
    }
}

</script>

<template>
    <footer>
        <div class="top_footer">
            <div class="container">
                <div class="row row-cols-5 py-5 justify-content-evenly">
                    <div class="col name">
                        <a class="navbar-brand text-light logo_scss" href="#"><span class="text_primary logo_scss_span">NEX</span>GEN</a>
                        <p class="mt-4">A functional HTML Template for Corporate and Business</p>
                        <ul class="p-0 mt-4 d-flex gap-3 flex-column" >
                            <li>
                                <h6>
                                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-telephone-fill" viewBox="0 0 16 16">
                                    <path fill-rule="evenodd" d="M1.885.511a1.745 1.745 0 0 1 2.61.163L6.29 2.98c.329.423.445.974.315 1.494l-.547 2.19a.678.678 0 0 0 .178.643l2.457 2.457a.678.678 0 0 0 .644.178l2.189-.547a1.745 1.745 0 0 1 1.494.315l2.306 1.794c.829.645.905 1.87.163 2.611l-1.034 1.034c-.74.74-1.846 1.065-2.877.702a18.634 18.634 0 0 1-7.01-4.42 18.634 18.634 0 0 1-4.42-7.009c-.362-1.03-.037-2.137.703-2.877L1.885.511z"/>
                                    </svg>
                                    {{ cell_number }}</h6>
                            </li>
                            <li>
                                <h6>
                                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-envelope-fill" viewBox="0 0 16 16">
                                      <path d="M.05 3.555A2 2 0 0 1 2 2h12a2 2 0 0 1 1.95 1.555L8 8.414.05 3.555ZM0 4.697v7.104l5.803-3.558L0 4.697ZM6.761 8.83l-6.57 4.027A2 2 0 0 0 2 14h12a2 2 0 0 0 1.808-1.144l-6.57-4.027L8 9.586l-1.239-.757Zm3.436-.586L16 11.801V4.697l-5.803 3.546Z"/>
                                    </svg>
                                    {{ email }}</h6>
                            </li>
                            <li>
                                <h6>
                                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-geo-alt-fill" viewBox="0 0 16 16">
                                      <path d="M8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10zm0-7a3 3 0 1 1 0-6 3 3 0 0 1 0 6z"/>
                                    </svg>
                                    {{ address }}</h6>
                            </li>
                        </ul>

                        <button class="btn mt-4 btn_border text-light text_size">GET IN TOUCH</button>
                    </div>
                    <div class="col bg-dark pt-4 pb-4">
                        <h2 class=" ps-3 pb-5">About</h2>
                        <ul class="d-flex flex-column gap-3">
                            <li v-for="item in about">
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-chevron-right" viewBox="0 0 16 16">
                                  <path fill-rule="evenodd" d="M4.646 1.646a.5.5 0 0 1 .708 0l6 6a.5.5 0 0 1 0 .708l-6 6a.5.5 0 0 1-.708-.708L10.293 8 4.646 2.354a.5.5 0 0 1 0-.708z"/>
                                </svg>
                                {{ item }}
                            </li>
                          
                        </ul>
                    </div>
                    <div class="col bg-dark pt-4 pb-4">
                        <h2 class=" ps-3 pb-5">Transport</h2>
                        <ul class="d-flex flex-column gap-3">
                            <li v-for="item in transport">
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-chevron-right" viewBox="0 0 16 16">
                                  <path fill-rule="evenodd" d="M4.646 1.646a.5.5 0 0 1 .708 0l6 6a.5.5 0 0 1 0 .708l-6 6a.5.5 0 0 1-.708-.708L10.293 8 4.646 2.354a.5.5 0 0 1 0-.708z"/>
                                </svg>
                                {{ item }}
                            </li>
                        </ul>
                    </div>
                    <div class="col bg-dark pt-4 pb-4">
                        <h2 class=" ps-3 pb-5">Support</h2>
                        <ul class="d-flex flex-column gap-3">
                            <li v-for="item in support ">
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-chevron-right" viewBox="0 0 16 16">
                                  <path fill-rule="evenodd" d="M4.646 1.646a.5.5 0 0 1 .708 0l6 6a.5.5 0 0 1 0 .708l-6 6a.5.5 0 0 1-.708-.708L10.293 8 4.646 2.354a.5.5 0 0 1 0-.708z"/>
                                </svg>
                                {{ item }}
                            </li>
                        </ul>
                    </div>

                </div>
            </div>
        </div>
        <div class="bottom_footer d-flex justify-content-between">
            
            <p class=" align-self-center ps-3">Enjoy the low price. We are tracking any intention of piracy.</p>
            <p class=" align-self-center pe-3"> @2020 NEXGEN is Proudly Powered by <span style="color: aquamarine;">Codings</span></p>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
@use './scss/partials/variables.scss' as *;


footer{
    color: white;
}
.top_footer{
   
    background-color: $bg-primary;
    li{
        list-style-type: none
        ;
    }
}

.bottom_footer{
    height: 100px;
    background-color: black;
    padding-left: 2rem;
    padding-right: 2rem;
}
.logo_scss{
        font-size: 2rem;
        font-weight: 700;
    }

    .logo_scss_span{
        border-top-left-radius: 40px;
        border-bottom-left-radius: 40px;
        background-color: $primary-transparent;
        padding: 3px;
        padding-left: 35px;
        padding-right: 5px;
        margin-right: 5px;
    }

    .text_primary{
        color: $primary;
    }

    .bg_primary{
        background-color: $primary;
    }
    .btn_border{
        border-color: $primary;
    }
   

</style>