<template>
 <div class="coffee">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'Coffee',
  props: {
    msg: String
  }
}
</script>