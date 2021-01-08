<template>
  <v-app>
    <div class="grey lighten-4">
      <Navbar />
      <v-main class="mx-10 mb-10">
        <router-view></router-view>
      </v-main>
    </div>
  </v-app>
</template>

<script>
import Navbar from "@/components/Navbar";

export default {
  name: "App",
  components: { Navbar },
  data: () => ({
    //
  })
};
</script>
