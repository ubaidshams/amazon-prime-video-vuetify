<template>
  <div class="familyFriendly">
    <div class="familyFriendlyBg"></div>
    <div
      class="familyFriendlyContent d-flex flex-column alig-start justify-center pa-15"
    >
      <h1 class="font-weight-medium">Family Friendly</h1>
      <p>
        With easy to use Parental Controls and a dedicated kids page, enjoy
        secure, ad-free kids entertainment. Kids can enjoy popular TV shows like
        Peppa Pig, Powerpuff Girls, and Chhota Bheem.
      </p>
      <v-btn color="#0f79af" class="white--text" width="280" height="54"
        >get started</v-btn
      >
    </div>
  </div>
</template>

<script>
export default {
  name: "FamilyFriendly",
};
</script>

<style scoped>
.familyFriendly {
  width: 100%;
  height: 70vh;
  display: flex;
  background: #000;
  color: #eee;
  flex-direction: row-reverse;
  background: url("https://m.media-amazon.com/images/G/01/digital/video/Magellan_MLP/IN-kids-30Jan._CB1517304519_.jpg");
  background-repeat: no-repeat;
  /* background-position: center; */
  background-size: cover;
  object-fit: cover;
}
.familyFriendlyBg {
  width: 50%;
  height: inherit;
}
.familyFriendlyContent {
  width: 50%;
  gap: 20px;
  background-image: linear-gradient(to right,  rgba(0, 0, 0, 0.804));
  height: inherit;
  background-size: cover;
}
p {
  padding-right: 20px;
  font-size: 1.25rem;
  font-weight: 300;
}
</style>
