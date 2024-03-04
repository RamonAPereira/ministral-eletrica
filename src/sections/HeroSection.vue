<script setup>
import Button from "../components/Button.vue";
</script>

<template>
  <section class="hero">
    <div class="hero__container">
      <h1 class="hero__title">MINISTRAL ELETRICA</h1>
      <p class="hero__description">
        Nos somos um servico que você pode confiar
      </p>
      <Button text="Entre em contato" link="#" is-primary="true" />
    </div>
  </section>
</template>

<style scoped>
.hero {
  background: url("./src/assets/hero__bg.jpg") no-repeat center center/cover;
  height: 100vh;
  padding: 0 2rem 0 2rem;
  display: flex;
  justify-content: center;
  align-items: center;
}
.hero__container {
  align-items: flex-start;
  display: flex;
  flex-direction: column;
  gap: 0.375rem;
  justify-content: center;
}
.hero__title {
  color: #fff9db;
  font-size: 2rem;
  font-weight: 700;
}
.hero__description {
  color: #fff9db;
  font-size: 1rem;
  font-weight: 400;
}

@media (min-width: 900px) {
  .hero {
    padding: 0 8rem 0 8rem;
    justify-content: flex-start;
  }
  .hero__container {
    gap: 0.75rem;
  }
  .hero__title {
    font-size: 4rem;
  }
  .hero__description {
    font-size: 2rem;
  }
}
</style>
