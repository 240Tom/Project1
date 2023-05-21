<!-- child components -->
<!-- Create a prop for 'Listen on spotify' -->
<template>
  <b-button class="CTA">{{ btnText }}</b-button>
</template>
<script>
export default {
  props: ["btnText"],
};
</script>

<style>
.CTA {
  background-color: black;
  color: white;
}
</style>
