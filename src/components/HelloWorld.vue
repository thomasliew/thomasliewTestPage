<template>
  <div class="container">
    {{ msg }}
  </div>
</template>

<script setup>
import { ref, onMounted } from "vue";
const msg = ref("1");

onMounted(() => {
  console.log(msg.value);
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
