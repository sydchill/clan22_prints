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
            All of your T-shirt <br />
            printing needs
          </p>
          <p class="subtitle primary-color mt-3 is-size-5">
            Send us your designs we will print for you
          </p>

          <a class="defaultbtn" href="mailto:clan22@clan22.com">Contact us</a>
        </div>
      </div>
    </section>
    <section id="offer" class="m-6">
      <h1
        class="title has-text-centered primary-color is-capitalized"
        style="font-weight: 900"
      >
        What do we offer
      </h1>

      <div class="columns mt-6">
        <div class="column m-5">
          <h1
            class="
              subtitle
              primary-color
              has-text-centered has-text-weight-semibold
            "
          >
            T-Shirts
          </h1>
          <div class="card">
            <div class="card-image">
              <figure class="image is-4by5">
                <img src="~/assets/img/tshirt.jpg" alt="Placeholder image" />
              </figure>
            </div>
            <div class="card-content tertiary-backround">
              <div class="content primary-color has-text-weight-semibold is-capitalized	">
                Bring your own T-shirt or we will buy one for you
              </div>
            </div>
          </div>
        </div>
        <div class="column m-5">
          <h1
            class="
              subtitle
              primary-color
              has-text-centered has-text-weight-semibold
            "
          >
            Tote bags/ Aprons
          </h1>
          <div class="card">
            <div class="card-image">
              <figure class="image is-4by5">
                <img src="~/assets/img/tote.jpg" alt="Placeholder image" />
              </figure>
            </div>
            <div class="card-content tertiary-backround">
              <div class="content primary-color has-text-weight-semibold is-capitalized	">
                We make our own bags and aprons but if your bags that you want
                heat pressed we got you covered
              </div>
            </div>
          </div>
        </div>
        <div class="column m-5">
          <h1
            class="
              subtitle
              primary-color
              has-text-centered has-text-weight-semibold
            "
          >
            Stickers/Labels
          </h1>
          <div class="card">
            <div class="card-image">
              <figure class="image is-4by5">
                <img src="~/assets/img/sticker-1.jpg" alt="Placeholder image" />
              </figure>
            </div>
            <div class="card-content tertiary-backround">
              <div class="content primary-color has-text-weight-semibold is-capitalized	">
                You have a sticker design we got you covered. We print and send
                you your stickers. We only takes orders for 20 stickers and
                above
              </div>
            </div>
          </div>
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

<style scoped>
 .card-content {
   min-height: 150px;
 }
</style>
