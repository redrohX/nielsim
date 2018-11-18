<template>
  <div class="o-wrapper">
    <div class="o-layout">
      <nav class="o-layout__item c-nav">
        <ul class="o-list-inline u-margin-none">
          <nuxt-link
            tag="li"
            to="/"
            class="o-list-inline__item u-margin-right-small">
            <a class="c-nav-link u-color-white has-light-focus">Home</a>
          </nuxt-link>
          <nuxt-link
            tag="li"
            to="blog"
            class="o-list-inline__item u-margin-right-small">
            <a class="c-nav-link u-color-white has-light-focus">Blog</a>
          </nuxt-link>
        </ul>
      </nav>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.c-nav {
  font-family: 'IBM Plex Mono', monospace;
  font-size: 2rem;
}

.c-nav-link {
  text-decoration: none;
}
</style>
