<template>
  <v-app>
    <v-main>
      <v-content style="height:10000px;">
        <v-contianer>
          <v-row>
            <v-col cols="10"></v-col>
            <v-col cols="2">
              <h1>Hello World!</h1>
            </v-col>
          </v-row>
        </v-contianer>
      </v-content>
    </v-main>
    <top-btn />
  </v-app>
</template>

<script>
import TopBtn from "./components/TopBtn.vue";
export default {
  name: "App",

  components: {
    TopBtn,
  },

  data: () => ({
    //
  }),
};
</script>
