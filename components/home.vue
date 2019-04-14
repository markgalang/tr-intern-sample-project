<template lang="pug">
    .hero.is-medium
      div#home
        navbar 
        .container.hero-body
            .columns.is-vcentered
                .column.is-half
                    h1.title.has-text-white.
                         Revolutionising Conveyancing through Digitisation
                    br
                    p.subtitle.has-text-white.
                        ConvX is a technology platform that will automate and commoditise the mostly manual process of
                        transferring land ownership
                    button.button.is-medium.is-fullwidth.has-text-white Sign Up


</template>

<script>
import navbar from '~/components/navbar.vue'

export default {
    components:{
        navbar
    }
}
</script>

<style>

</style>
