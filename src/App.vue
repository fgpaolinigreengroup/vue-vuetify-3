<template>
  <v-app>
    <!-- SIDEBAR -->
    <SideBar/>
  <v-main>
    <!-- CARDS   -->
  </v-main>
  </v-app>
</template>

<script>


import SideBar from './components/SideBar.vue';

export default {
  name: 'App',

  components: {
    SideBar
},

  data: () => ({
    //
  }),
}
</script>
