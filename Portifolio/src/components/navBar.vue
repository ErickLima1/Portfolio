<template>
  <div>
    <v-app-bar fiat class="border-b">
      <v-app-bar-title><v-chip  variant="outlined">Meu Portifolio</v-chip></v-app-bar-title>
      <v-space></v-space>
      <v-btn @click="scroll('sobre')">Sobre</v-btn>
      <v-btn @click="scroll('projeto')">Projetos</v-btn>
      <v-btn @click="scroll('contato')">Contato</v-btn>

      <v-menu>
        <template #activator="{ props }">
            <v-avatar  class="mr-2" v-bind="props">
              <v-img cover src="../assets/img/eae0f89dd900459c8c7a98092d15e789.png"></v-img>
            </v-avatar>
          </template>
          <v-card min-with="200px">
            <v-list :lines="false" density="compact">
                <v-list-item prepend-icon="mdi-cog">
                    <v-btn>
                        <v-list-item>Backend</v-list-item>
                    </v-btn>
                </v-list-item>
            </v-list>
            <v-list :lines="false" density="compact">
                <v-list-item prepend-icon="mdi-pencil-ruler">
                    <v-btn>
                        <v-list-item>Frontend</v-list-item>
                    </v-btn>
                </v-list-item>
            </v-list>
          </v-card>
      </v-menu>
    </v-app-bar>
  </div>
</template>

<script>
  export default {
    methods: {
      scroll(refName) {
        const element = document.getElementById(refName);
        element.scrollIntoView({behavior: "smooth"});


      }
    }
  };
</script>