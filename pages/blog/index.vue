<template>
  <article>
    <h1>Blog post title</h1>
    <p>
      <strong>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean venenatis placerat erat sit amet eleifend. Nam est enim, eleifend nec nunc et, aliquam posuere massa. Proin et augue iaculis, congue orci id, varius urna. Pellentesque imperdiet non risus nec accumsan. Phasellus egestas ante ante, et fermentum tellus suscipit vel. Praesent purus enim, molestie vitae turpis ut, eleifend viverra mauris. Suspendisse non semper libero. Morbi ultricies turpis velit, quis egestas eros volutpat et. Proin vitae tortor sem. Phasellus eleifend varius diam quis varius. Morbi nec elementum ligula, ac tincidunt risus. Integer sodales elit eu neque convallis, nec varius magna elementum. Nulla et molestie nisl, vitae facilisis quam.</strong>
    </p>
    <p>
      Sed sed enim vitae <a href="/">urna blandit aliquet</a> eget ac nisi. Proin a mollis ligula. Quisque ac vehicula ex. Aenean tristique turpis ut velit egestas, a vulputate tellus tempor. Sed bibendum tellus id risus euismod semper. Morbi pulvinar libero quis porta laoreet. Donec blandit malesuada quam, nec consectetur erat lobortis sed. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Nunc ut justo non magna accumsan iaculis ac nec enim. Mauris congue orci dolor, id mattis mauris iaculis id. Praesent metus velit, accumsan sed aliquet ac, congue eu risus. Nunc sagittis, libero vitae viverra dignissim, arcu tortor tincidunt est, ac fringilla augue nisl sed orci. Quisque accumsan orci eget porta efficitur.
    </p>
    <p>
      Sed egestas gravida justo vel finibus. Donec ut ligula id nibh rhoncus accumsan. Vestibulum gravida ultrices quam vitae blandit. Cras nec ex faucibus, pellentesque erat eu, aliquet ante. Duis eu ligula id risus eleifend ultrices non vitae orci. Vestibulum egestas urna eu odio egestas tristique. Donec volutpat lorem sit amet orci pharetra convallis sed ac est.
    </p>
  </article>
</template>

<style>
.red {
  color: red;
}
</style>

<script>
export default {
  data() {
    return {
      title: 'This is a blog index'
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
