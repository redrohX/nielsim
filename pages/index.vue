<template>
  <div>
    <logo/>
    <h1>Index page heading</h1>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean venenatis placerat erat sit amet eleifend. Nam est enim, eleifend nec nunc et, aliquam posuere massa. Proin et augue iaculis, congue orci id, varius urna. Pellentesque imperdiet non risus nec accumsan. Phasellus egestas ante ante, et fermentum tellus suscipit vel. Praesent purus enim, molestie vitae turpis ut, eleifend viverra mauris. Suspendisse non semper libero. Morbi ultricies turpis velit, quis egestas eros volutpat et. Proin vitae tortor sem. Phasellus eleifend varius diam quis varius. Morbi nec elementum ligula, ac tincidunt risus. Integer sodales elit eu neque convallis, nec varius magna elementum. Nulla et molestie nisl, vitae facilisis quam.
    </p>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  },
  data() {
    return {
      title: 'Welcome to Niels.im'
    }
  },
  head() {
    return {
      title: this.title,
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'My custom description'
        }
      ]
    }
  }
}
</script>
