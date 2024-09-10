<script setup>
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';
import GateauxGroupes from './components/GateauxGroupes.vue';
import GateauxIndividuels from './components/GateauxIndividuels.vue';
import GateauxVoyages from './components/GateauxVoyages.vue';
import Contacts from './components/Contacts.vue';
import Histoire from './components/Histoire.vue';
</script>

<template>
  <Header></Header>
  <main>
    <section id="histoire">
      <Histoire />
    </section>
    <section id="groupes">
      <GateauxGroupes />
    </section>
    <section id="individuels">
      <GateauxIndividuels />
    </section>
    <section id="voyages">
      <GateauxVoyages />
    </section>
    <section id="contacts">
      <Contacts />
    </section>
  </main>
  <Footer></Footer>
</template>

<style scoped>
</style>
