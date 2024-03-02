<script setup>
//import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <!--<HelloWorld msg="Vite + Vue" />-->
  <main>
    <section class="hero">
      <div class="hero__container">
        <h1 class="hero__title">MINISTRAL ELETRICA</h1>
        <p class="hero__description">
          Nos somos um servico que você pode confiar
        </p>
        <a class="hero__button" href="#"
          >Entre em contato <i class="bi bi-whatsapp"></i
        ></a>
      </div>
    </section>
  </main>
</template>

<style scoped>
.hero {
  background: url("./assets/hero__bg.jpg") no-repeat center center/cover;
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
.hero__button {
  display: inline-block;
  font-size: 1rem;
  font-weight: 700;
  color: #f3da65;
  border: 1px solid #f3da65;
  padding: 0.625rem 1rem 0.625rem 1rem;
}
.hero__button:hover {
  transition: 0.3s;
  background-color: #075e54;
  border-color: #075e54;
  color: #fff9db;
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
  .hero__buton {
    font-size: 1.375rem;
  }
}
</style>
