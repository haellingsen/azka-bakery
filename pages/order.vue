<template>
  <div class="mh-100">
    <AppBanner cursive="delightful" title="products" class="mb-5" />

    <OrderProductType
      type="lefse"
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
