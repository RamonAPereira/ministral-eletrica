<script setup>
defineProps({
  backGroundImg: String,
});
</script>
<template>
  <div class="card">
    <span class="card__title"><slot></slot></span>
  </div>
</template>
<style scoped>
.card {
  width: 100%;
  max-width: 23.938rem;
  height: 17.25rem;
  display: flex;
  align-items: flex-end;
  background: url("../assets/service-one.jpg") no-repeat center center / cover;
  border-radius: 0.625rem;
}
.card__title {
  display: inline-block;
  width: 100%;
  background: #1bc35e;
  text-align: center;
  border-radius: 0 0 0.625rem 0.625rem;
  height: 3.938rem;
}
</style>
