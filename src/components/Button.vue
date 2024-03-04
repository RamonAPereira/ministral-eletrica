<script setup>
defineProps({
  text: String,
  link: String,
  isPrimary: Boolean,
});
</script>
<template>
  <a
    class="button"
    :class="isPrimary ? 'button--primary' : 'button--secondary'"
    href="`${link}`"
    >{{ text }}</a
  >
</template>

<style scoped>
.button {
  display: inline-block;
  font-size: 1rem;
  font-weight: 700;
  padding: 0.625rem 0 0.625rem 0;
  width: 12rem;
  text-align: center;
}
.button--primary {
  color: #f3da65;
  border: 1px solid #f3da65;
}
.button--secondary {
  background-color: #1bc35e;
  color: #fff9db;
}
.button:hover {
  transition: 0.3s;
  background-color: #075e54;
  border-color: #075e54;
  color: #fff9db;
}
@media (min-width: 900px) {
  .button {
    font-size: 1.375rem;
  }
}
</style>
