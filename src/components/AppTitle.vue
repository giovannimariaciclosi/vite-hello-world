<script>
export default {
  data() {
    return {
      title: "La mia prima app con Vite! :)",
    };
  },
};
</script>

<template>
  <h1>
    <font-awesome-icon icon="fa-solid fa-rocket" />
    {{ title }}
    <font-awesome-icon icon="fa-solid fa-rocket" />
  </h1>
</template>

<style>
h1 {
  color: black;
  text-align: center;
  padding-top: 1em;
  position: absolute;
  top: 200px;
  right: 0;
  left: 0;
}

.fa-rocket {
  padding: 0 1em;
  color: rgb(192, 25, 25);
}
</style>
