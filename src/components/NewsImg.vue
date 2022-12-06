<template>
  <!-- <v-card class="mx-auto" max-width="448">
    <v-layout>
      <v-app-bar color="primary" density="compact">
        <template v-slot:prepend>
          <v-app-bar-nav-icon></v-app-bar-nav-icon>
        </template>

        <v-app-bar-title>Photos</v-app-bar-title>

        <template v-slot:append>
          <v-btn icon="mdi-dots-vertical"></v-btn>
        </template>
      </v-app-bar> -->

  <v-card class="mx-auto" max-width="600" max-height="300">
    <v-layout>
      <v-main>
        <v-container fluid>
          <v-carousel height="300" width="100">
            <v-carousel-item>
              <v-row no-gutters>
                <v-col v-for="n in 3" :key="n" cols="12" sm="4" class="my-10">
                  <v-sheet class="ma-2 pa-2"
                    ><img
                      src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
                      alt=""
                      height="180"
                      width="180"
                  /></v-sheet>
                </v-col>
              </v-row>
            </v-carousel-item>

            <v-carousel-item>
              <v-row no-gutters>
                <v-col v-for="n in 3" :key="n" cols="12" sm="4" class="my-10">
                  <v-sheet class="ma-2 pa-2"
                    ><img
                      src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
                      alt=""
                      height="180"
                      width="180"
                  /></v-sheet>
                </v-col>
              </v-row>
            </v-carousel-item>
          </v-carousel>
        </v-container>
      </v-main>
    </v-layout>
  </v-card>
</template>
