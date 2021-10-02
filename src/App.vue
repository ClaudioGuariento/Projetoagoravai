<template>
  <v-app>
      <AppTopBar/>
          <v-main> 
        <Inicio/>
        <router-view/>
      </v-main>
    </v-app>
</template>

<script>
import Inicio from './views/Inicio.vue'
import AppTopBar from './components/shared/AppTopBar.vue'
export default {
  name: 'App', 
  component: {
    Inicio,
    AppTopBar
  },
};
</script>
