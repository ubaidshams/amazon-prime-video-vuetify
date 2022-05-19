<template>
  <div class="channelsComp d-flex justify-center align-center">
    <article class="d-flex justify-center">
      <div class="channelLeft d-flex flex-column pa-8">
        <h1>Your favorite channels all in one place</h1>
        <p>
          With Prime Video Channels, find shows and movies from your favorite
          channels all in one place. Enjoy with an add-on subscription to
          Channels of your choice
        </p>
      </div>
      <div class="channelList">
        <a href=""
          ><img
            src="https://m.media-amazon.com/images/G/31/AmazonVideo/2021/Channels/MLP/LionsgatePlay-426X2946_V1.jpg"
            alt=""
        /></a>
        <a href=""
          ><img
            src="https://m.media-amazon.com/images/G/31/AmazonVideo/2021/Channels/MLP/426x294_Discovery.jpg"
            alt=""
        /></a>

        <a href=""
          ><img
            src="https://m.media-amazon.com/images/G/31/AmazonVideo/2021/Channels/MLP/Erosnow-426X2948_V1.jpg"
            alt=""
        /></a>

        <a href=""
          ><img
            src="https://m.media-amazon.com/images/G/31/AmazonVideo/2021/Channels/MLP/hoichoi-426X2946_V1.jpg"
            alt=""
        /></a>

        <a href=""
          ><img
            src="https://m.media-amazon.com/images/G/31/AmazonVideo/2021/Channels/MLP/Docubay-426X2947_V1.jpg"
            alt=""
        /></a>

        <a href=""
          ><img
            src="https://m.media-amazon.com/images/G/31/AmazonVideo/2021/Channels/MLP/ShortsTV-426X2944_V1.jpg"
            alt=""
        /></a>

        <a href=""
          ><img
            src="https://m.media-amazon.com/images/G/31/AmazonVideo/2021/Channels/MLP/Mubi-426X2946_V1.jpg"
            alt=""
        /></a>
        <a href=""
          ><img
            src="https://m.media-amazon.com/images/G/31/AmazonVideo/2021/Channels/MLP/426x294_MANORAMAMAX.jpg"
            alt=""
        /></a>

        <a href=""
          ><img
            src="https://m.media-amazon.com/images/G/31/AmazonVideo/2021/Channels/Hayu_logo_for_MLP_Grid.jpg"
            alt=""
        /></a>
      </div>
    </article>
  </div>
</template>

<script>
export default {
  name: "ChannelsComp",
};
</script>

<style scoped>
.channelsComp {
  width: 100%;
  padding: 20px 0;
}
.channelsComp article {
  width: 90%;
}
.channelLeft {
  flex-basis: 50%;
  gap: 20px;
}
.channelLeft h1 {
  font-size: 3rem;
  font-weight: 300;
  line-height: 50px;
}
.channelLeft p {
  font-size: 1.5rem;
  font-weight: 300;
  line-height: 30px;
}
.channelList {
  flex-basis: 50%;
  display: flex;
  flex-wrap: wrap;
  column-gap: 8px;
}
.channelList a img {
  width: 220px;
  height: 154px;
  transition: all 0.2s linear;
}
.channelList a img:hover {
  box-shadow: 0 0 8px 5px #333;
  transform: scale(1.01);
}
</style>
