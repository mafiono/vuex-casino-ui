<template>
 <HomePage />
</template>

<script>
import HomePage from "@/components/HomePage";

export default {
  name: 'App',
  components: {
    HomePage,
  }
}
</script>

<style>
.container {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
</style>
