<template>
  <section
    class="categoriesDrop d-flex justify-space-between white--text text--accent-3"
  >
    <div class="catLeft d-flex justify-end pr-10">
      <div class="leftContent pt-5 d-flex flex-column pr-5 ml-15">
        <p>Top Categories</p>
        <div class="cardContainer d-flex flex-wrap">
          <v-img
            v-for="card in cardList"
            :key="card.src"
            :src="card.src"
            :width="card.width"
            :height="card.height"
            class="card d-flex justify-center align-center text-center rounded"
            >{{ card.text }}</v-img
          >
        </div>
      </div>
    </div>

    <div class="catRight"></div>
  </section>
</template>

<script>
export default {
  name: "CategoriesDrop",
  data() {
    return {
      cardList: [
        {
          src: "https://m.media-amazon.com/images/G/01/digital/video/web_cats/Included-With-Prime.png",
          width: 158,
          text: "Included with Prime",
          height: 90,
        },
        {
          src: "https://m.media-amazon.com/images/G/01/digital/video/web_cats/Amazon-Originals.png",
          width: "158",
          text: "Amazon Originals",
          height: "90",
        },
        {
          src: "https://m.media-amazon.com/images/G/01/digital/video/web_cats/Movies.png",
          width: "158",
          text: "Movies",
          height: "90",
        },
        {
          src: "https://m.media-amazon.com/images/G/01/digital/video/web_cats/TV-Shows.png",
          width: "158",
          text: "TV",
          height: "90",
        },
        {
          src: "https://m.media-amazon.com/images/G/01/digital/video/web_cats/Included-With-Prime.png",
          width: "158",
          text: "Kids",
          height: "90",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
.categoriesDrop {
  width: 100%;
  height: 50vh;
  background: #252e39;
  padding: 10px;
}
.catLeft {
  width: 50%;
  height: inherit;
  border-right: 1px solid #eee;
}
.cardContainer {
  width: 100%;
  height: inherit;
  gap: 10px;
}
v-image .leftContent {
  width: 70%;
  height: inherit;
}
.catRight {
  width: 45%;
  height: inherit;
}
</style>
