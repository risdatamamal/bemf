<template>
    <div class="b-container-fluid AppNavBar-font">
        <b-navbar toggleable="xl" fixed="top" class="mx-0 mx-lg-5 my-3">
            <b-navbar-brand href="#">LOREM</b-navbar-brand>
            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
            <b-collapse id="nav-collapse" is-nav class="col-12 col-xl-6 ml-auto">
                <!-- Right aligned nav items -->
                <b-navbar-nav class="row w-100 text-center mx-auto">
                    <div class="col-12 col-xl">
                        <b-nav-item to="/">Lorem</b-nav-item>
                    </div>
                    <div class="col-12 col-xl">
                        <b-nav-item-dropdown text="Lorem" right>
                            <b-dropdown-item href="#">Lorem</b-dropdown-item>
                            <b-dropdown-item href="#">Lorem</b-dropdown-item>
                            <b-dropdown-item href="#">Lorem</b-dropdown-item>
                            <b-dropdown-item href="#">Lorem</b-dropdown-item>
                        </b-nav-item-dropdown>
                    </div>
                    <div class="col-12 col-xl">
                        <b-nav-item to="/">Lorem</b-nav-item>
                    </div>
                    <div class="col-12 col-xl">
                        <b-nav-item to="/">Lorem</b-nav-item>
                    </div>
                    <div class="col-12 col-xl">
                        <b-nav-item to="/">Lorem</b-nav-item>
                    </div>
                    <div class="col-12 col-xl">
                        <b-nav-item to="/">Lorem</b-nav-item>
                    </div>
                </b-navbar-nav>
            </b-collapse>
        </b-navbar>
    </div>
</template>

<script>

export default {
    head() {
        return {
            link: [ 
                {
                    rel: 'stylesheet',
                    href: 'https://fonts.googleapis.com/css?family=Roboto&display=swap'
                }
            ]
        }
    }
}
</script>

<style>
.AppNavBar-font {
    font-family: Roboto, sans-serif !important;
    font-size: 18px;
    font-weight: 900 !important;
}

.navbar-brand {
    letter-spacing: 18px;
}

.navbar-light .navbar-brand, .navbar-light .navbar-nav .nav-link {
    color: #006fb7;
}
</style>