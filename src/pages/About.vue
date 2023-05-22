<template>
  <h1>This is the about page</h1>
</template>

<script lang="ts">
import Vue from "vue";
import NavBar from "~/components/NavBar.vue";
import TheLogo from "~/components/TheLogo.vue";

export default Vue.extend({
  name: "IndexPage",
  components: { TheLogo, NavBar },
  layout: "Mylayouts",
});
</script>
