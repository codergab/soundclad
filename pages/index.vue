<template>
  <section class="container">
    <div class="overlay">
      <div class="links">
        <h2 class="bigi head">SOUNDCLAD</h2>
        <nuxt-link
          to="/playlists"
          class="bigi b-2"
        >
        Start Listening
        </nuxt-link>
      </div>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style scoped>
  .head {
    color: #dd6b4d !important;
  }
</style>
