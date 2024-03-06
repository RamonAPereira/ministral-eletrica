<script setup>
import Button from "../components/Button.vue";
</script>

<template>
  <section class="weare">
    <div class="weare__container">
      <div class="weare__content">
        <h2 class="weare__title">NOS SOMOS A MINISTRAL ELETRICA</h2>
        <p class="ware__description">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer
          dignissim aliquet urna ut congue. Morbi libero elit, accumsan ut
          laoreet in, suscipit ac elit. Proin blandit rutrum nulla at congue.
          Nam felis magna, pellentesque ac est et, suscipit ullamcorper sapien.
          Mauris sed gravida augue. Praesent ac consequat enim. Phasellus quis
          commodo diam, nec molestie mauris.
        </p>
        <Button text="leia mais" link="#" />
      </div>
      <img class="weare__image" src="../assets/we-are-image.jpg" alt="" />
    </div>
  </section>
</template>

<style scoped>
.weare {
  background-color: #fff9db;
}
.weare__container {
  display: flex;
  flex-direction: row;
  justify-content: center;
  gap: 8rem;
  padding: 5.938rem 2rem 5.938rem 2rem;
}
.weare__content {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: center;
  max-width: 26.563rem;
  gap: 1.313rem;
}
.weare__title {
  font-size: 2.5rem;
}
.weare__description {
  font-size: 1.25rem;
}

@media (max-width: 900px) {
  .weare__image {
    display: none;
  }
  .weare__title {
    font-size: 2rem;
  }
}
</style>
