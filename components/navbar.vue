<template lang="pug">
    nav.navbar
        .container
            div.navbar-brand
                img(src="~/assets/images/favicon.png")
                p|
                    b  ConvX
            div.navbar-end
                ul.navbar-menu
                    li.navbar-item
                        nuxt-link(to="#") About Us
                    li.navbar-item
                        nuxt-link(to="#") Contact Us
                    li.navbar-item
                        nuxt-link(to="#") How It Works
                    li.navbar-item
                        nuxt-link(to="#").button.is-link Sign In
</template>

<script>
export default {

}
</script>

<style>

</style>
