<style scoped>
.section-login {
    background-size: cover;
}

.add-gradient {
    background-image: linear-gradient(to bottom, #FF4F74, #FF9BA6);
    color: #fff;
    padding: 5px 80px;
    border-radius: 50px;
}


</style>
<template>
    <section class="section section-login my-0 p-0" :style="{'background-image':'url(img/theme/login-banner.png)'}">
        <div class="">
            <div class="row justify-content-center align-items-center" id="login-screen">
                <div class="col-lg-4 offset-md-2 offset-0">
                    <card type="transparent"
                          property="nowrap" 
                          header-classes="bg-white pb-5"
                          body-classes="px-lg-5 py-lg-5 bg-transparent"
                          class="border-0">
                                                      <template>
                            <div class="d-block text-center">
                                <img src="/img/theme/logo.png" alt="" srcset="" class="mw-100">
                                <h1>Sign In</h1>
                                <h3 class="mb-5">Please  Login  to  Continue</h3>
                            </div>
                            
                        </template>
                        <template>
                            <form role="form">
                                
                                <base-input alternative
                                            direction="column"
                                            class="mb-3 shadow-none"
                                            inputClasses="bg-transparent border-bottom border-dark rounded-0"
                                            label="Name"
                                            required
                                            placeholder="Email">
                                </base-input>
                                <base-input alternative
                                            direction="column"
                                            class="mb-3 shadow-none"
                                            inputClasses="bg-transparent border-bottom border-dark rounded-0 w-100 position-relative"
                                            label="Password"
                                            required
                                            types="password"
                                            placeholder="Password"
                                            addonRightIcon="fa fa-eye">
                                </base-input>
                                                  <div class="row my-3">
                                                    <div class="col-12 text-right">
                                                        <a href=".#/forgot-password" class="text-dark">
                                                            <small>Forgot password?</small>
                                                        </a>
                                                    </div>
                                                </div>
                                <div class="text-center">
                                    <base-button class="my-4 add-gradient text-white" is="a">Sign In</base-button>
                                </div>
                            </form>
                        </template>
                    </card>
                </div>
                <div class="col-lg-6">
                        <img src="/img/theme/login-people.png" alt="" srcset="" class="mw-100">
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {};
</script>
<style>
</style>
