<template>
  <div>
    <button @click="route">test</button>
  </div>
</template>
<script>
export default {
  methods: {
    route() {
      console.log("test");
      this.$router.push("/dessin/1");
    }
  }
};
</script>
<style lang=""></style>
