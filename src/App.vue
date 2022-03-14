<template>
  <div id="app" class="container">
    <div class="row py-4">
      <Profil />
    </div>
  </div>
</template>

<script>
import Profil from "./components/Profil.vue";

export default {
  name: "App",
  components: {
    Profil,
  },
};
</script>
