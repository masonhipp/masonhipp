<template>
  <div>
    <!-- <nav class="navbar is-transparent" role="navigation" aria-label="main navigation">
      <div class="container">
        <div class="navbar-brand mh-logo">
           <Logo class="mh-logo" />
         </div>
        <div class="navbar-menu" id="navMenu">
          <div class="navbar-start"></div>
          <div class="navbar-end"><a class="navbar-item" href="/mentorship">Mentorship</a>
            <div class="navbar-item"><a class="button is-primary is-outlined is-rounded" href="/contact">Say Hello</a></div>
          </div>
        </div>
      </div>
    </nav> -->

    <section class="main-content">
      <nuxt />
    </section>
  </div>
</template>

<script>
import Logo from '~/components/Logo'

export default {
  components: {
    Logo
  },
  data () {
    return {
    }
  }
}
</script>

<style lang="scss" scoped>
.navbar{
  padding: 20px 0px;

  .mh-logo {
    font-weight:bold;
    text-transform: uppercase;
    display:flex;
    align-items:center;
  }
}
</style>