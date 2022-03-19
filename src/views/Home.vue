<template>
  <div class="home">
    <Player />
  </div>
</template>

<script>
import Player from "../components/Player";
export default {
  components: {
    Player,
  },
};
</script>

<style scpoed>
.home {
  display: flex;
  width: 100%;
  height: 100%;
  background-image: linear-gradient(to right,#a6c1ee,#fbc2ed);

  z-index: 0;
  position: relative;
  justify-content: center;
  align-items: center;
}
</style>