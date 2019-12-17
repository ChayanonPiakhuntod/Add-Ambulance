<template>
  <v-app>
     
    <v-app-bar app class="orange darken-2">
      <v-toolbar-title class="headline text-uppercase" >
        <span>AMBULANCE</span>

      </v-toolbar-title>
      <v-spacer></v-spacer>
    </v-app-bar>
      <v-content>
          <router-view />
      </v-content>
  </v-app>
</template>

<script>
    export default {
        name: "App",
        data() {
            return {
            };
        },
        methods: {
            login() {
                this.$router.push("/");
            }
        }
    };
</script>
