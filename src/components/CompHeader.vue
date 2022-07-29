<script lang="ts">
export default {
  name: "CompHeader",
  data: () => ({}),
};
</script>
<template>
  <v-app-bar width="100%" height="120">
    <v-row justify="space-around">
      <div
        width="63%"
        max-height="120"
        class="ma-6 d-flex align-center"
      >
        <div class="pb-8 pr-15 mt-6 ml-16 d-flex align-self-center">
          <v-img
            height="100%"
            width="200"
            aspect-ratio="1.3"
            src="src/assets/img/Logocerto.png"
          ></v-img>
        </div>

        

        <div class="ma-4 pb-3 mt-15" >
          <v-row justify="end">
            <span class="ma-9 text-black"> SUPORTE <br>+55 (67)99850-....</span>
            <v-icon
              class="ma-5 pt-3"
              icon="fa:fab fa-twitter"
              large
              color="black"
            >
            </v-icon>
            <v-icon
              class="ma-5 pt-3"
              large
              icon="fa:fab fa-facebook"
              color="black"
              
            >
            </v-icon>
            <v-icon
              class="ma-5 pt-3"
              large
              icon="fa:fab fa-youtube"
              color="black"
            >
            </v-icon>
            <v-btn class="mt-7 ml-15 bg-green" color="white">Trabalhe Conosco</v-btn>
            <v-btn class="mt-7 ml-15 bg-green" color="white">Area do Cliente</v-btn>
          </v-row>
          <span></span>
          <v-row justify="end">
            <v-btn color="white">Home</v-btn>
            <v-btn color="white">Empreendimentos</v-btn>
            <v-btn color="white">ESG</v-btn>
            <v-btn color="white">Compre um lote</v-btn>
            <v-btn color="white">Sobre nós</v-btn>
            <v-btn color="white">Fale com a gente</v-btn>
          </v-row>
        </div>
      </div>
    </v-row>
  </v-app-bar>
</template>
