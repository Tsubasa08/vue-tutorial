<script>
export default {
  data() {
    return {
      message: 'Hello World!',
    };
  },
};
</script>

<template>
  <h1>{{ message }}</h1>
  <div>{{ message.split('').reverse().join('') }}</div>
</template>
