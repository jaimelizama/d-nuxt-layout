<template>
  <v-container>
    <v-row>
      <v-col
        v-for="(character, id) in $store.state.characters"
        :key="id"
        cols="12"
        sm="6"
        md="4"
      >
        <v-card class="mx-auto" max-width="auto">
          <v-img class="align-end" :src="character.imagen"> </v-img>
          <v-card-title>{{ character.nombre }}</v-card-title>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {}
</script>

<style></style>
