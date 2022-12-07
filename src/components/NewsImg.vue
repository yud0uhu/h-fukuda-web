<template>
  <div class="pl-8 pt-4 pb-4">
    <v-row no-gutters class="text-center">
      <v-col cols="5">
        <p class="text-left">NEWS</p>
        <v-progress-linear
          class="pb-3 mb-3"
          model-value="100"
          color="brak"
        ></v-progress-linear>
      </v-col>
      <v-col cols="5"
        ><p class="mt-3 text-h5 text-left ml-3">お知らせ</p></v-col
      >
      <v-card class="mx-auto" max-width="600" max-height="300">
        <v-layout>
          <v-main>
            <v-container fluid>
              <v-carousel height="250" width="100">
                <v-carousel-item>
                  <v-row no-gutters>
                    <v-col v-for="n in 3" :key="n" cols="12" sm="4">
                      <v-sheet class="mr-2"
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
                    <v-col v-for="n in 3" :key="n" cols="12" sm="4">
                      <v-sheet class="mr-2"
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
    </v-row>
  </div>
</template>

<style scoped>
p {
  color: brak;
}
</style>
