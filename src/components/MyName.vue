<template>
  <h1>{{ name }}</h1>
</template>

<script>
export default {
  props: {
    name: String
  },
}
</script>

<style>
h1 {
  position: absolute;
  top: 50%;
  left: 50%;
  font-weight: bold;
  margin-right: -50%;
  transform: translate(-50%,-50%);
}
</style>
