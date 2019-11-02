<template>
  <div id="app" class="">
    <h2>Каталог фильмов</h2>
    <input v-model="query" type="text" placeholder="Введите название">
    <section>
      <div class="container-fluid">
          <div class="row">
              <div class="col-12 col-md-6 col-lg-4">
                <div class="card">card</div>
              </div>
              <div class="col-12 col-md-6 col-lg-4">
                <div class="card">card</div>
              </div>
              <div class="col-12 col-md-6 col-lg-4">
                <div class="card">card</div>
              </div>
          </div>
      </div>
    </section>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    // HelloWorld
  },
  data() {
    return {
      query: '',
    };
  },
};
</script>

<style lang="scss">
  $grid-gutter-width: 6px;
  @import "bootstrap/scss/bootstrap-grid.scss";

  .card {
    background-color: yellow;
  }

</style>
