<template>
  <div>
    <site-header />
    <section role="main">
      <div class="o-wrapper">
        <div class="o-layout">
          <div class="o-layout__item u-1/2@tablet">
            <nuxt/>
          </div>
        </div>
      </div>
    </section>
    <site-footer />
  </div>
</template>

<script>
import SiteHeader from '~/components/Header.vue'
import SiteFooter from '~/components/Footer.vue'

export default {
  components: {
    SiteHeader,
    SiteFooter
  }
}
</script>

<style scoped>
.green {
  color: green;
}
</style>
