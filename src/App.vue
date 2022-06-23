<template>
  <div id="app" class="container">
    <div class="row">
      <map-component></map-component>
    </div>
    <!-- <div class="col-md-3">
      <layers-checkbox></layers-checkbox>
    </div> -->
  </div>
</template>

<script>
// import LayersCheckbox from './components/LayersCheckbox.vue'
import MapComponent from './components/MapComponent.vue'


export default {
  name: 'App',
  components: {
    MapComponent,
    // LayersCheckbox
  }
}
</script>

<style>

</style>
