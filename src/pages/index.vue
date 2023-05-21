<template>
  <TheHeader></TheHeader>
</template>

<script lang="ts">
import Vue from "vue";
import NavBar from "~/components/NavBar.vue";
import TheLogo from "~/components/TheLogo.vue";

export default Vue.extend({
  name: "IndexPage",
  components: { TheLogo, NavBar },
});
</script>
