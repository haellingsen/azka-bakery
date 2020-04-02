<template>
  <div class="mh-100">
    <AppBanner cursive="lekre" title="lefser" class="mb-5" />

    <OrderProductType
      type="lefser"
      title="lefser med lange tradisjoner"
      data-aos="flip-left"
    />
    <OrderProductType
      type="flatbrød"
      title="flatbrød"
      data-aos="flip-right"
    />
  </div>
</template>

<script>
import AppBanner from "@/components/app-banner";
import OrderProductType from "@/components/order-product-type";

export default {
  components: {
    AppBanner,
    OrderProductType
  }
};
</script>
