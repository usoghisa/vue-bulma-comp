<template>
  <div class="some-custom-css">
    <b-box>
      <b-media>
        <b-media-left>
          <b-image is-64x64>
            <img src="http://bulma.io/images/placeholders/128x128.png" alt="Image">
          </b-image>
        </b-media-left>
        <b-media-content>
          <b-content>
            <p>
              <strong>John Smith</strong>
              <small>@johnsmith</small>
              <small>31m</small>
              <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean efficitur sit amet massa fringilla egestas. Nullam condimentum luctus turpis.
            </p>
          </b-content>
        </b-media-content>
      </b-media>
    </b-box>
    <b-button is-primary>Primary</b-button>
    <b-button is-info>Info</b-button>
    <b-button is-success is-loading>Success</b-button>
    <b-button is-warning>Warning</b-button>
    <b-button is-danger>Danger</b-button>

    <div class="card">
      <div class="card-image">
        <figure class="image is-4by3">
          <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
        </figure>
      </div>
      <div class="card-content">
        <div class="media">
          <div class="media-left">
            <figure class="image is-48x48">
              <img src="https://bulma.io/images/placeholders/96x96.png" alt="Placeholder image">
            </figure>
          </div>
          <div class="media-content">
            <p class="title is-4">John Smith</p>
            <p class="subtitle is-6">@johnsmith</p>
          </div>
        </div>

        <div class="content">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit.
          Phasellus nec iaculis mauris.
          <a>@bulmaio</a>.
          <a href="#">#css</a>
          <a href="#">#responsive</a>
          <br>
          <time datetime="2016-1-1">11:09 PM - 1 Jan 2016</time>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.some-custom-css {
  margin: 2em;
}
.button {
  margin: 0.2em;
}
</style>
