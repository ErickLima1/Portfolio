<template>
  <v-app id="projeto">
    <div>
      <h1 class="text-center mb-5">Projetos</h1>
      <v-divider class="mx-4 mb-1"></v-divider>
      <v-row>
        <v-col cols="12" sm="6" md="4" lg="3" class="mb10">
          <v-card>
            <v-img class="align-end text-white" src="../assets/img/api.png">
            </v-img>
            <v-card-item>
              <v-card-title>ApiRegistroWorks</v-card-title>
              <v-divider class="mx-4 mb-1"></v-divider>
            </v-card-item>
            <div class="px-3">
              <v-chip-group v-model="selection">
                <v-chip>Node.Js</v-chip>

                <v-chip>JavaScript</v-chip>

                <v-chip>Mysql</v-chip>

                <v-chip>Swagger</v-chip>
              </v-chip-group>
              <v-card-actions>
                <a href="https://github.com/ErickLima1/BackEnd-RegisterWorks" target="_blank">
                  <v-btn prepend-icon="mdi-github" variant="outlined" color="primary" class="mr-2">GitHub</v-btn>
                </a>
                <a href="https://backend-registerworks.vercel.app/api-docs-ui/#/registerUser" target="_blank">
                  <v-btn prepend-icon="mdi-google-chrome" variant="tonal" color="error">Site</v-btn>
                </a>
              </v-card-actions>
            </div>
          </v-card>
        </v-col>

        <!---Aqui-->
        <v-col cols="12" sm="6" md="4" lg="3" class="mb10">
          <v-card>
            <v-img class="align-end text-white" src="../assets/img/todolist.png">
            </v-img>
            <v-card-item>
              <v-card-title>TodoList</v-card-title>
              <v-divider class="mx-4 mb-1"></v-divider>
            </v-card-item>
            <div class="px-3">
              <v-chip-group v-model="selection">
                <v-chip>Node.Js</v-chip>

                <v-chip>JavaScript</v-chip>

                <v-chip>Mysql</v-chip>

                <v-chip>Express</v-chip>

              </v-chip-group>
              <v-card-actions>
                <a href="https://github.com/ErickLima1/todoList-Backend/tree/main" target="_blank">
                  <v-btn prepend-icon="mdi-github" variant="outlined" color="primary" class="mr-2">GitHub</v-btn>
                </a>
                <a href="https://todo-list-front-end-vert.vercel.app/" target="_blank">
                  <v-btn prepend-icon="mdi-google-chrome" variant="tonal" color="error">Site</v-btn>
                </a>
              </v-card-actions>
            </div>
          </v-card>
        </v-col>

        <v-col cols="12" sm="6" md="4" lg="3" class="mb10">
          <v-card>
            <v-img class="align-end text-white" src="../assets/img/manutenção.png">
            </v-img>
            <v-card-item>
              <v-card-title>BlogPost</v-card-title>
              <v-divider class="mx-4 mb-1"></v-divider>
            </v-card-item>
            <div class="px-3">
              <v-chip-group v-model="selection">
                <v-chip>Node.Js</v-chip>

                <v-chip>JavaScript</v-chip>

                <v-chip>MongoDB</v-chip>

                <v-chip>Handlebars</v-chip>

              </v-chip-group>

              <v-card-actions>
                <a href="https://github.com/ErickLima1/blogPosts" target="_blank">
                  <v-btn prepend-icon="mdi-github" variant="outlined" color="primary" class="mr-2">GitHub</v-btn>
                </a>
                <v-btn prepend-icon="mdi-cog" variant="tonal" color="error">Fora Do Ar</v-btn>
              </v-card-actions>
            </div>
          </v-card>
        </v-col>

        <v-col cols="12" sm="6" md="4" lg="3" class="mb10">
          <v-card>
            <v-img class="align-end text-white" src="../assets/img/apiSupermercado.png">
            </v-img>
            <v-card-item>
              <v-card-title>ApiSupermercado </v-card-title>
              <v-divider class="mx-4 mb-1"></v-divider>
            </v-card-item>
            <div class="px-3">
              <v-chip-group v-model="selection">
                <v-chip>Node.Js</v-chip>

                <v-chip>TypeScript</v-chip>

                <v-chip>Postgres</v-chip>

                <v-chip>Swagger</v-chip>

              </v-chip-group>

              <v-card-actions>
                <a href="https://github.com/ErickLima1/blogPosts" target="_blank">
                  <v-btn prepend-icon="mdi-github" variant="outlined" color="primary" class="mr-2">GitHub</v-btn>
                </a>
                <v-btn prepend-icon="mdi-google-chrome" variant="tonal" color="error">Fora Do Ar</v-btn>
              </v-card-actions>
            </div>
          </v-card>
        </v-col>
      </v-row>
    </div>
  </v-app>
</template>

<script>

</script>
