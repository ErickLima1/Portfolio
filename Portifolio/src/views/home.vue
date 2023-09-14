<template>
    <v-app id="sobre">
      <v-container fluid>
        <v-card fiat class="border mb-4 mx-auto">

          <v-row align="center" >
            <v-col cols="12" md="6" sm="6" >
              <v-img src="../assets/img/eae0f89dd900459c8c7a98092d15e789.png" alt="Sua Foto" max-height="500" class="mr-2 ml-1 elevation-26"></v-img>
            </v-col>

            <v-col cols="12" md="6" class="text hidden-xs-only" >
              <div class="preencher">
                <h2 class="text-grey">Olá, eu sou Erick Lima</h2>
                <h2 class="text-grey mb-4">Desenvolvedor backend & Frontend</h2>
                <p>Estou atualmente cursando Ciência da Computação e já acumulo três anos de experiência na área de programação. Inicialmente, minha jornada foi voltada para o desenvolvimento no backend, com foco em tecnologias como JavaScript, Node.js e TypeScript. Ao longo meu do tempo, meu interesse naturalmente expandiu para o frontend, com destaque para a linguagem Vue.js e seus frameworks.</p>
                <br>
                <a href="https://www.linkedin.com/in/erick-lima-dev/" target="_blank">
                  <v-btn prepend-icon="mdi-linkedin" variant="outlined" class="mr-3 mt-11" >LinkedIn</v-btn>

                </a>
                <a href="https://github.com/ErickLima1" target="_blank">
                  <v-btn prepend-icon="mdi-github" variant="outlined" class="mt-11">GitHub</v-btn>
                </a>
              </div>

            </v-col>
          </v-row>
        </v-card>
      </v-container>
      <v-divider class="mx-4 mb-1"></v-divider>
    </v-app>
  </template>
  
  <style scoped>
    .preencher {
      padding: 24px;
    }

  </style>
  