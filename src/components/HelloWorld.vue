<template>
  <h1>{{ title }}</h1>
</template>

<script>
export default {
  name: "HelloWorld", // PascalCase for consistency
  data() {
    return {
      title: "This message is from custom template",
    };
  },
};
</script>

<style scoped></style>
