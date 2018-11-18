<template>
  <header
    id="header"
    role="banner"
    class="c-header u-margin-bottom">
    <div class="o-wrapper">
      <div class="o-layout">
        <div class="o-layout__item">
          <div class="c-logo"><span class="c-logo__underline">Niels</span>.im</div>
        </div>
      </div>
    </div>
    <navigation />
  </header>
</template>

<script>
import Navigation from '~/components/Navigation.vue'

export default {
  components: {
    Navigation
  }
}
</script>

<style lang="scss" scoped>
@import 'node_modules/sass-mq/mq';

.c-header {
  background: #001aff;
}

.c-logo {
  color: white;
  display: inline-block;
  font-family: 'IBM Plex Mono', monospace;
  font-size: 48px;
  font-weight: bold;
  line-height: 1;
  margin-bottom: 24px;
  padding: 0 0 1.5rem 0;
  text-transform: uppercase;

  @include mq($from: tablet) {
    font-size: 78px;
  }
}

.c-logo__underline {
  border-bottom: 12px solid currentColor;
}
</style>
