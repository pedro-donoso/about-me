<template>
  <div id="app">
    <the-desktop-nav id="desktop-nav" />
    <div class="view-container">
      <router-view />
    </div>
  </div>
</template>

<script>
import TheDesktopNav from "@/components/TheDesktopNav";
export default {
  components: {
    TheDesktopNav,
  },
};
</script>


<style lang="scss" scoped>
.view-container {
  width: 80%;
  padding: 1rem;
  margin-left: 7rem;
}
</style>
