<template>
    <div class="main-sidebar h-100 rounded-3 shadow ">
            <div class="justify-content-end py-3 text-center">
                    <router-link slot="brand" class="navbar-brand mr-lg-5" to="/">
                    <img src="img/theme/logo.png" alt="logo">
                </router-link>
                <ul class="navbar-nav ml-lg-auto flex-column text-left justify-content-center mt-4">
                    <li class="nav-item px-5">
                        <a class="nav-link nav-link-icon" href="#" target="_blank" rel="noopener"
                        data-toggle="tooltip" title="Like us on Facebook">
                            <img src="img/theme/dashboard.png" alt="" class="pr-2">
                            <span class="nav-link-inner--text">Dashboard</span>
                        </a>
                    </li>
                    <li class="nav-item px-5">
                        <a class="nav-link nav-link-icon" href="#"
                        target="_blank" rel="noopener" data-toggle="tooltip" title="Follow us on Instagram">
                            <img src="img/theme/user.png" alt="" class="pr-2">
                            <span class="nav-link-inner--text">Users</span>
                        </a>
                    </li>
                    <li class="nav-item px-5">
                        <a class="nav-link nav-link-icon" href="#" target="_blank" rel="noopener"
                        data-toggle="tooltip" title="Follow us on Twitter">
                            <img src="img/theme/Vector.png" alt="" class="pr-2">
                            <span class="nav-link-inner--text">Reported</span>
                        </a>
                    </li>
                    <li class="nav-item px-5">
                        <a class="nav-link nav-link-icon" href="#"
                        target="_blank" rel="noopener" data-toggle="tooltip" title="Star us on Github">
                            <img src="img/theme/Icon-inbox.png" alt="" class="pr-2">
                            <span class="nav-link-inner--text">Feedbacks</span>
                        </a>
                    </li>
                </ul>
            </div>
            <ul class="navbar-nav ml-lg-auto flex-column text-left justify-content-center mt-4 h-50">
                    <li class="nav-item px-5">
                        <a class="nav-link nav-link-icon border-top border-danger rounded-0 pt-5" href="#"
                        target="_blank" rel="noopener" data-toggle="tooltip" title="Star us on Github">
                            <img src="img/theme/log-out.png" alt="" class="pr-2">
                            <span class="nav-link-inner--text">Logout</span>
                        </a>
                    </li>
            </ul>
    </div>
</template>

<style>
</style>
