<!-- child components -->
<!-- Create a prop for 'Listen on spotify' -->
<template>
  <!-- using the value with the prop below -->
  <b-button class="CTA" href:="url">{{ btnText }} </b-button>
</template>

<script>
//simplified defintion of props//
export default {
  props: ["btnText", "url"],
};

// Looking at this for notes
// const props = defineProps({
//   //props - how we accepts input into a component.
//   orderreverse: {
//     type: Boolean,
//     default: false,
//     required: false,
//   },
// });
</script>

<style>
.CTA {
  background-color: black;
  color: white;
}
</style>
