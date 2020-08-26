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
  width: 85%;
  padding: 0.5rem;
  margin-left: 6rem;
}
</style>
