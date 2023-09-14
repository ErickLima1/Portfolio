<template>
  <v-app theme="dark">
    <navBar/>
    <v-main>
      <v-container>
        <home/>
        <card/>
        <contato/>
      </v-container>
      <rodape/>
    </v-main>
  </v-app>
</template>

<script setup>
  import { ref } from 'vue';
  import navBar from './components/navBar.vue';
  import home from './views/home.vue';
  import card from './components/cardProjeto.vue'
  import contato from './components/contato.vue';
  import rodape from './components/footer.vue';
</script>
