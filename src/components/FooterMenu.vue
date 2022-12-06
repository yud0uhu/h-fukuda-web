<template>
  <v-layout>
    <v-footer
      class="txet-clor text-center d-flex flex-column"
      :style="{
        'background-image': `url(${require('../assets/Footer.jpg')})`,
      }"
    >
      <div class="pl-8 pt-4 pb-4">
        <v-row no-gutters class="text-center">
          <v-col cols="5">
            <p class="text-left">CONTACT</p>
            <v-progress-linear
              class="pb-3 mb-3"
              model-value="100"
              color="white"
            ></v-progress-linear>
          </v-col>
          <v-col cols="5"
            ><p class="mt-3 text-h5 text-left ml-3">問い合わせ</p></v-col
          >
          <v-col cols="12" class="pl-10">
            <p class="font-weight-bold text-center">連絡先メールアドレス</p>
          </v-col>
          <v-col cols="12">
            <p class="font-weight-medium">
              <v-btn
                v-for="icon in icons"
                :key="icon"
                class="mx-4"
                :icon="icon"
                variant="text"
              ></v-btn>
              h-fukuda@photon.chitose.jp
            </p>
          </v-col>
        </v-row>
      </div>

      <!-- <p class="text-white text-h3">
          <v-progress-linear model-value="100"></v-progress-linear>

          問い合わせ
        </p> -->

      <v-divider></v-divider>
    </v-footer>
  </v-layout>
</template>

<script>
export default {
  data: () => ({
    icons: ["mdi-email"],
  }),
};
</script>
<style scoped>
p {
  color: white;
}
</style>
