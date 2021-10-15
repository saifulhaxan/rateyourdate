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
            <div class="row justify-content-center align-items-center">
                <div class="col-lg-4 offset-md-2 offset-0">
                    <card type="transparent"
                          property="nowrap" 
                          header-classes="bg-white pb-5"
                          body-classes="px-lg-5 py-lg-5 bg-transparent"
                          class="border-0">
                        <template>
                            <div class="d-block text-center">
                                <img src="/img/theme/logo.png" alt="" srcset="" class="mw-100">
                                <h1>Forgot Password</h1>
                                <h5 class="mb-5">Please reset your password</h5>
                            </div>
                        </template>
                        <template>
                            <form role="form">
                            
                                 <base-input alternative
                                            direction="column"
                                            class="mb-3 shadow-none"
                                            inputClasses="bg-transparent border-bottom border-dark rounded-0 w-100 position-relative"
                                            label="New Password"
                                            required
                                            types="password"
                                            placeholder="New Password"
                                            addonRightIcon="fa fa-eye">
                                </base-input>

                                 <base-input alternative
                                            direction="column"
                                            class="mb-3 shadow-none"
                                            inputClasses="bg-transparent border-bottom border-dark rounded-0 w-100 position-relative"
                                            label="Confirm Password"
                                            required
                                            types="password"
                                            placeholder="Re-type passowrd"
                                            addonRightIcon="fa fa-eye">
                                </base-input>
                                <div class="text-center">
                                    <base-button class="my-4 add-gradient text-white border-none" icon="fa fa-chevron-right">Update</base-button>
                                    <div class="back-to-login mt-3">
                                        <a href=".#/login" class="text-dark"><i class="fa fa-arrow-left pr-2"></i> Back  to login</a>
                                    </div>
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
