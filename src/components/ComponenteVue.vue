<template>
  <div>
    <img class="nodo" :src="data.src" alt="" />
    <h2>{{ data.nombre }}</h2>
  </div>
</template>

<script>
export default {
  name: "imagenesData",
  props: {
    data() {
      return {
        type: Object,
        default: () => {},
      };
    },
  },
};
</script>
<style scoped>
.nodo {
  margin: 0 auto;
  border-radius: 50%;
  border: 2px solid #ccc;
}
</style>
