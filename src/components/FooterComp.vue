<template>
  <div class="footerBlock d-flex justify-center align-center">
    <article class="d-flex flex-column align-center">
      <a href="">
        <img
          src="https://m.media-amazon.com/images/G/01/digital/video/acquisition/web_footer_logo._CB462908456_.png"
          alt="footer-logo"
        />
      </a>
      <div class="footerBottom d-flex justify-center">
        <div class="footerLinks">
          <a href="">Terms and Privacy Notice</a>
          <a href="">Send us feedback</a>
          <a href="">Help</a>
        </div>
        <p>© 1996-2022, Amazon.com, Inc. or its affiliates</p>
      </div>
    </article>
  </div>
</template>

<script>
export default {
  name: "FooterComp",
};
</script>

<style scoped>
.footerBlock {
  width: 100%;
  height: 20vh;
}
a {
  text-decoration: none;
  font-size: 14px;
  padding: 5px;
}
p {
  font-size: 14px;
  font-weight: 100;
  color: #efefef;
}
</style>
