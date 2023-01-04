<script>
export default {
  data() {
    return {
      message: 'Hello World!',
      titleClass: 'title',
    };
  },
};
</script>

<template>
  <h1 :class="titleClass">{{ message }}</h1>
  <div>{{ message.split('').reverse().join('') }}</div>
</template>

<style>
.title {
  color: red;
}
</style>
