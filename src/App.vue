<template>
  <v-app>
    <v-app-bar color="primary" fixed app>
      <v-toolbar-title>Eth Ate</v-toolbar-title>
    </v-app-bar>
    <v-main>
      <v-container>
        <RestaurantScreen />
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
import RestaurantScreen from '@/components/RestaurantScreen';
export default {
  name: 'App',
  components: {RestaurantScreen},
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
