<template>
    <div>
        <v-app-bar
      app
      
      
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="@/assets/logo.jpg"
          transition="scale-transition"
          width="40"
        />

        <label>{{ $const.APP_NAME }}</label>
        </div>

      <v-spacer></v-spacer>

      <v-btn text>Login</v-btn>
      <v-icon>mdi-account-circle</v-icon>
      
    </v-app-bar>


    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

</style>