<template>
  <div>
    <h1>{{ title }}</h1>
  </div>
</template>

<script>
export default {
  name: "MyTitle",

  data() {
    return {
      title: "La mia prima app con Vue CLI!",
    };
  },
};
</script>

<style scoped></style>
