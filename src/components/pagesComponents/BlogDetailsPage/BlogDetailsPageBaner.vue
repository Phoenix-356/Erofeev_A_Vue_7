<template>
  <section class="banner-details center"></section>
</template>

<script>
export default {
  name: "BlogDetailsPageBaner",

  data() {
    return {};
  },

  mounted() {},

  methods: {},
};
</script>

<style lang="scss" scoped>
.banner-details {
  background-image: url("../../../assets/images/blog-details-header.jpg");
  height: 356px;
}
.center {
  padding-left: calc(50% - 1200px / 2);
  padding-right: calc(50% - 1200px / 2);
}
</style>
