<template>
  <div>
    <WelcomeImage />
    <v-container>
      <v-row justify="center">
        <v-btn
          color="primary"
          elevation="2"
          outlined
          x-large
          @click="$router.push('/personajes')"
          >Ver Personajes</v-btn
        >
      </v-row>
    </v-container>
  </div>
</template>

<style>
body {
  background-color: #262c3a;
}
</style>
