<script>
export default{
    name: 'PageFooter'
}

</script>

<template>
    <footer>
        <div class="top_footer">
            <div class="container">
                <div class="row row-cols-5 py-5 justify-content-evenly">
                    <div class="col name">
                        <h1 class="text-center">NEXGEN</h1>
                        <p>A functional HTML Template for Corporate and Business</p>
                        <ul>
                            <li>
                                <h5>+1(305) 1234-56789</h5>
                            </li>
                            <li>
                                <h5>hello@example.com</h5>
                            </li>
                            <li>
                                <h5>Main Avenue,987</h5>
                            </li>
                        </ul>

                        <button class="btn btn-outline-primary"> GET IN TOUCH</button>
                    </div>
                    <div class="col bg-dark pt-4 pb-4">
                        <h2 class=" ps-3 pb-5">Lorem</h2>
                        <ul class="d-flex flex-column gap-3">
                            <li>  Lorem, ipsum.</li>
                            <li>  Lorem, ipsum.</li>
                            <li>  Lorem, ipsum.</li>
                            <li>  Lorem, ipsum.</li>
                            <li>  Lorem, ipsum.</li>
                        </ul>
                    </div>
                    <div class="col bg-dark pt-4 pb-4">
                        <h2 class=" ps-3 pb-5">Lorem</h2>
                        <ul class="d-flex flex-column gap-3">
                            <li>  Lorem, ipsum.</li>
                            <li>  Lorem, ipsum.</li>
                            <li>  Lorem, ipsum.</li>
                            <li>  Lorem, ipsum.</li>
                            <li>  Lorem, ipsum.</li>
                        </ul>
                    </div>
                    <div class="col bg-dark pt-4 pb-4">
                        <h2 class=" ps-3 pb-5">Lorem</h2>
                        <ul class="d-flex flex-column gap-3">
                            <li>  Lorem, ipsum.</li>
                            <li>  Lorem, ipsum.</li>
                            <li>  Lorem, ipsum.</li>
                            <li>  Lorem, ipsum.</li>
                            <li>  Lorem, ipsum.</li>
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

</style>