<template>
  <li>
    <b-button class="SocialMediaIcon">{{ btnText }}</b-button>
    <b-button class="CTA">{{ btnText }}</b-button>
    <b-button class="CTA">{{ btnText }}</b-button>
    <b-button class="CTA">{{ btnText }}</b-button>
    <b-button class="CTA">{{ btnText }}</b-button>
    <!-- computed property, link to access the icon, only add the code here -->
  </li>
</template>

<script>
export default {
  props: ["btnText"],
};
</script>
