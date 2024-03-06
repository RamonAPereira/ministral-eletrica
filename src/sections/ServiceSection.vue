<script setup>
import ServiceCard from "../components/ServiceCard.vue";
</script>

<template>
  <section class="services">
    <h2 class="services__title">NOSSOS SERVIÇOS</h2>
    <div class="services__cards">
      <ServiceCard>teste</ServiceCard>
      <ServiceCard>teste2</ServiceCard>
    </div>
  </section>
</template>

<style scoped>
.services {
  display: flex;
  width: 100%;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 5.938rem 2rem 5.938rem 2rem;
  gap: 3.5rem;
}
.services__title {
  font-size: 2rem;
}
.services__cards {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 100%;
  gap: 3.5rem;
}
</style>
