<template>
  <div class="banner">
    <p class="banner-text">this is a banner</p>
  </div>
</template>

<script>
export default {
  name: "MyHero",
};
</script>

<style>
.banner {
  height: 400px;
  background-image: url("https://source.unsplash.com/random");
  background-position: center;
  background-repeat: no-repeat;
  width: 100%;
}
.banner-text {
  font-size: 3em;
  color: black;
}
</style>
