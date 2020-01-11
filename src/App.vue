<template>
  <v-app>
    
    <div data-v-4d77a948="" class="v-application--wrap" >
      <div id="app">
        <app-header></app-header>
        <app-content></app-content>
        <app-footer></app-footer>
      </div>
    </div>
      
  </v-app>
</template>

<script>
import AppHeader from './components/AppHeader.vue';
import AppContent from './components/AppContent.vue';
import AppFooter from './components/AppFooter.vue';


export default {
  name: 'App',

  components: {
    AppHeader,
    AppContent,
    AppFooter
  },

  data: () => ({ 
  
  
  }),
};
</script>

<style scoped>
    element.style {
        background: #0d0b4d;
}
  .v-application--wrap {
    background-color:#0d192e;
  }
</style>
