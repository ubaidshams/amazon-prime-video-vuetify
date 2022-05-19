<template>
  <div class="bannerBottom">
    <div class="bannerBottomContent">
      <h1>Movie rentals on Prime Video</h1>
      <h3>Early Access to New Movies, Before Digital Subscription</h3>
      <v-btn
        color="#0F79AF"
        width="280"
        height="54"
        class="white--text text--lighten-3 mt-5"
        >Rent now</v-btn
      >
    </div>
  </div>
</template>

<script>
export default {
  name: "BannerBottom",
};
</script>

<style scoped>
.bannerBottom {
  width: 100%;
  height: 70vh;
  background: url("https://m.media-amazon.com/images/G/31/AmazonVideo/2021/X-site/MLP/TVOD/MLP_TVOD_KGF2.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  color: #eee;
}
.bannerBottomContent {
  width: 50%;
  height: 100%;
  padding: 120px 64px;
  display: flex;
  flex-direction: column;
  gap: 20px;
}
</style>
