<template>
  <Tutorial />
</template>

<script>
export default {
  name: "IndexPage",
  created() {
    console.log(this.$axios);
  },
  async asyncData(context) {
    // console.log(context, "context");
  },
};
</script>
