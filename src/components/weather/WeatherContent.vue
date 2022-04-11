<template>
  <div class="weather-wrapper">
    <ContentHeader />
    <CitySelector />
  </div>
</template>

<script>
import CitySelector from "./CitySelector.vue";
import ContentHeader from "./ContentHeader.vue";
export default {
  name: "WeatherContent",
  components: {
    ContentHeader,
    CitySelector,
  },
};
</script>

<style></style>
