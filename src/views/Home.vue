<template>
  <div class="home">
    <first />
  </div>
</template>

<script>
// @ is an alias to /src
import first from "@/components/first.vue";

export default {
  name: "Home",
  components: {
    first,
  },
};
</script>

<style scoped>
.home {
}
</style>
