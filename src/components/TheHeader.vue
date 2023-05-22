<!-- The parent component  -->
<template>
  <header class="Header">
    <TheLogo></TheLogo>
    <NavBar></NavBar>
    <CtaButton
      btn-text="Listen on Spotify"
      url="http://spotify.com"
    ></CtaButton>
  </header>
</template>

<style>
.Header {
  display: flex;
  background-color: black;
  height: 200px;
  margin: auto;
  width: 100%;
  padding: 10px;
  align-items: center;
}
</style>
