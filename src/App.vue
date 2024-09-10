<script setup>
import Header from './components/Header.vue';
import Cakes from './components/Cakes.vue';
import Footer from './components/Footer.vue';
import Tartes from './components/Tartes.vue';
import Entremets from './components/Entremets.vue';
import Macarons from './components/Macarons.vue';
import Chouquettes from './components/Chouquettes.vue';
import Contacts from './components/Contacts.vue';
import Histoire from './components/Histoire.vue';
</script>

<template>
  <Header></Header>
  <main>
    <section id="histoire">
      <Histoire />
    </section>
    <section id="cakes">
      <Cakes />
    </section>
    <section id="tartes">
      <Tartes />
    </section>
    <section id="entremets">
      <Entremets />
    </section>
    <section id="macarons">
      <Macarons />
    </section>
    <section id="chouquettes">
      <Chouquettes />
    </section>
    <section id="contacts">
      <Contacts />
    </section>
  </main>
  <Footer></Footer>
</template>

<style scoped>
</style>
