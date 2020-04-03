<template>
  <div class="container-fluid py-5 d-flex justify-content-center">
    <div class="container mx-auto row">
      <div class="col-lg-6 text-center" data-aos="fade-left">
        <AppTitle
          class="text-dark"
          color="dark"
          cursive="Bli kjent med"
          title="VÅR HISTORE"
        />

        <AppIndexContent
          content="Med denne nettsiden har vi lyst å vise deg tre ting. For det første vårt rike sortement av tradisjonsbakst, hvem vi er og historien bak bakeriet, og sist men ikke minst hvor vi holder til, så du kan komme innom på en uforglemmelig smaksopplevelse mens du unner deg en kaffetår i vår koselige kaffestue."
          link="om oss"
          to="about"
        />
      </div>

      <div class="col-lg-6 pic" data-aos="fade-right">
        <div class="img-wrapper">
          <img
            class="hvr-grow img-fluid"
            src="@/assets/img/about.jpg"
            alt="Food"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import AppTitle from "./app-title";
import AppIndexContent from "./app-index-content";

export default {
  components: {
    AppTitle,
    AppIndexContent
  }
};
</script>

<style lang="scss" scoped>
.pic {
  margin-top: 3rem;

  @media (min-width: 992px) {
    margin-top: 0;
  }
}
</style>
