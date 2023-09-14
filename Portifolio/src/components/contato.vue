<template>
    <v-app id="contato">
    <div>
        <v-divider class="mx-4 mb-1"></v-divider>
        <h1 class="text-center mb-8">Contato</h1>
        <v-divider class="mx-4 mb-1"></v-divider>
        <v-row>
            <v-col  cols="12" sm="6" md="4" lg="3" class="mb10">
                <v-card>
                <v-card-actions>
                    <a>
                        <v-btn prepend-icon="mdi-email-alert" variant="outlined" 
                        color="primary" class="mr-2">Email</v-btn>                        
                    </a>
                  </v-card-actions>
                  <p class="ml-2">ericklimacosta29@gmail.com</p>
                </v-card>
            </v-col>
            <v-col  cols="12" sm="6" md="4" lg="3" class="mb10">
                <v-card>
                <v-card-actions>
                    <a>
                        <v-btn prepend-icon="mdi-cellphone" variant="outlined" 
                        color="primary" class="mr-2">Telefone</v-btn>                        
                    </a>
                  </v-card-actions>
                  <p class="ml-2">(91)985076719</p>
                </v-card>
            </v-col>
            <v-col  cols="12" sm="6" md="4" lg="3" class="mb10">
                <v-card>
                <v-card-actions>
                    <a href="https://www.linkedin.com/in/erick-lima-dev/" target="_blank">
                        <v-btn prepend-icon="mdi-linkedin" variant="outlined" 
                        color="primary" class="mr-2">Linkedin</v-btn>                        
                    </a>
                  </v-card-actions>
                  <p class="ml-2">@ErickCosta</p>
                </v-card>
            </v-col>
            <v-col  cols="12" sm="6" md="4" lg="3" class="mb10">
                <v-card>
                <v-card-actions>
                    <a href="https://github.com/ErickLima1" target="_blank">
                        <v-btn prepend-icon="mdi-github" variant="outlined" 
                        color="primary" class="mr-2">GitHub</v-btn>                        
                    </a>
                  </v-card-actions>
                  <p class="ml-2">@ErickLima</p>
                </v-card>
            </v-col>
        </v-row>
    </div>
</v-app>

</template>

<style scoped>
    .preencher {
        padding: 24px;
    }

</style>