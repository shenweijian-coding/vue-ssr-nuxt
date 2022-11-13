<!-- Please remove this file from your project -->
<template>
  <div>
    <h3>{{ count }}</h3>
    <h4>{{ msg }}</h4>
    <button @click="click">click</button>
  </div>
</template>

<script>
export default {
  name: "NuxtTutorial",
  data() {
    return {
      count: 0,
      msg: null,
    };
  },
  methods: {
    click() {
      console.log("点击了");
      this.count++;
    },
  },
};
</script>
