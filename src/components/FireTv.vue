<template>
  <div class="fireTv">
    <div class="fireTvBg"></div>
    <div
      class="fireTvContent d-flex flex-column alig-start justify-center pa-15"
    >
      <h1 class="font-weight-medium">Even better with Fire TV Stick</h1>
      <p>
        The biggest movies and TV shows are always better on a big screen.
        Simply plug in your Amazon Fire TV Stick and stream on any HDTV. Press
        the voice button on the remote and say the name of the title you want to
        watch to find it in seconds.
      </p>
      <v-btn color="#0f79af" class="white--text" width="280" height="54"
        >get started</v-btn
      >
    </div>
  </div>
</template>

<script>
export default {
  name: "FireTv",
};
</script>

<style scoped>
.fireTv {
  width: 100%;
  height: 70vh;
  display: flex;
  background: url("https://images-na.ssl-images-amazon.com/images/G/01/digital/video/Magellan_MLP/MLP_Template_Image_Left.jpg");
  background-repeat: no-repeat;
  object-fit: cover;
  background-size: cover;
  color: #eee;
}
.fireTvBg {
  width: 50%;
  height: inherit;
}
.fireTvContent {
  width: 50%;
  gap: 20px;
  background-image: linear-gradient(to left, rgba(0, 0, 0, 0.804));
  height: inherit;
  background-size: cover;
}
p {
  padding-right: 20px;
  font-size: 1.25rem;
  font-weight: 300;
}
</style>
