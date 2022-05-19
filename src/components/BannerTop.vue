<template>
  <div class="banner">
    <div class="bannerContent">
      <h1>Welcome to Prime Video</h1>
      <h3 class="font-weight-regular">
        Join Prime to watch the latest movies, TV shows and award-winning Amazon
        Originals
      </h3>
      <v-btn
        color="#0f79af"
        width="280"
        height="48"
        class="px-5 py-3 white--text tetx-lighten-3 font-weight-light"
        >Start your 30-day free trial</v-btn
      >
      <p class="ml-6">With select credit or debit cards</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "BannerTop",
};
</script>

<style scoped>
.banner {
  background: url("https://m.media-amazon.com/images/G/31/AmazonVideo/2019/MLP.jpg");
  width: 100%;
  height: 70vh;
  background-repeat: no-repeat;
  background-size: cover;
  backdrop-filter: blur(5px);
}
.bannerContent {
  width: 50%;
  height: 100%;
  display: flex;
  flex-direction: column;
  color: #eee;
  gap: 10px;

  background-image: linear-gradient(to right,#000, rgba(0, 0, 0, 0.7));
  padding: 100px 64px;
  background-size: cover;
}
.bannerContent h1 {
  font-size: 2.5rem;
  font-weight: 300;
}
.bannerContent h3 {
  font-size: 1.4rem;
  font-weight: 100;
}
</style>
