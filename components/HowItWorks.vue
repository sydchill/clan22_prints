<template>
  <div id="how_it_woks">
    <section class="hero tertiary-backround is-halfheight pt-3">
      <!-- Hero head: will stick at the top -->
      <div class="hero-head">
        <Navigation />
      </div>
      <!-- Hero content: will be in the middle -->
      <div class="hero-body">
        <div class="container has-text-centered">
          <p class="title primary-color is-size-1" style="font-weight: 900">
            How It works
          </p>
        </div>
      </div>
    </section>
    <section class="m-5">
      <div class="columns m-6">
        <div class="column m-6">
          <figure class="image is-128x128">
            <img src="@/assets/img/send.png" />
          </figure>
          <div class="block">
            <h1
              class="
                title
                is-size-4
                has-text-centered
                primary-color
                has-text-weight-bold
                is-capitalized
              "
            >
              Send design
            </h1>
          </div>
        </div>
        <div class="column m-6">
          <figure class="image is-128x128">
            <img src="@/assets/img/heatpress.png" />
          </figure>
          <div class="block">
            <h1
              class="
                title
                is-size-4
                has-text-centered
                primary-color
                has-text-weight-bold
                is-capitalized
              "
            >
              We print it for you
            </h1>
          </div>
        </div>
        <div class="column m-6">
          <figure class="image is-128x128">
            <img src="@/assets/img/deliver.png" />
          </figure>
          <h1
            class="
              title
              is-size-4
              has-text-centered
              primary-color
              has-text-weight-bold
              is-capitalized
            "
          >
            Deliver to your door step
          </h1>
        </div>
      </div>
    </section>
    <!-- footer -->
    <Footer />
  </div>
</template>
        

<style scoped>
figure {
  margin: auto !important;
}


</style>
