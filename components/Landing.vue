<template>
  <div id="landing">
    <section class="hero tertiary-backround is-medium pt-3">
      <!-- Hero head: will stick at the top -->
      <div class="hero-head">
        <Navigation />
      </div>
      <!-- Hero content: will be in the middle -->
      <div class="hero-body">
        <div class="container has-text-centered">
          <p class="title primary-color is-size-1" style="font-weight: 900">
            All of your T-shirt <br> printing needs
          </p>
          <p class="subtitle primary-color mt-3 is-size-5">Send us your designs we will print for you</p>

          <a class="defaultbtn" href="mailto:clan22@clan22.com">Contact us</a>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "Landing",
};
</script>
