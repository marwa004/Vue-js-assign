<template>
  <v-app>
 <MainBar/>
 <v-main>
        <router-view></router-view>
    </v-main>
    
  </v-app>
</template>

<script setup>

import MainBar from './components/MainBar.vue'

</script>
