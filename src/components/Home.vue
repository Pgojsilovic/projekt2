<template>
  <v-container>
    <v-row>
      <v-col cols="10" sm="8">
        <v-row align="center">
          <v-col cols="6">
            <v-img
                contain
                width="512"
                :src="require('../assets/videotomp3.png')">
            </v-img>
          </v-col>
          <v-col cols="6">
            <h2>Pretvori Youtube video u MP3 u samo jednom kliku!</h2>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
    <v-row class="text-center">
      <v-col class="text-center">
        <router-link style="text-decoration: none" to="/konverter">
          <v-btn
              tile
              color="#FF0000"
              style="color: white"
          >Započni!</v-btn>
        </router-link>
      </v-col>

    </v-row>
  </v-container>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Home",

  components: {
  },
}
</script>

<style scoped>

</style>