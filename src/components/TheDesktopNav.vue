<template>
  <section class="nav">
    <div class="nav__logo">
      <img src="../assets/images/foto.jpg" alt="logo" class="nav__image" />
    </div>
    <div class="nav__menu">
      <ul class="menu__list">
          <li><a href="https://github.com/pedro-donoso" class="menu__item">Github</a></li>
          <br>
        <li><a href="https://www.linkedin.com/in/pedro-donoso/" class="menu__item">Linkedin</a></li>
        <br>
        <li><a href="https://app.netlify.com/teams/pedro-donoso/sites" class="menu__item">Netlify</a></li>
      </ul>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.nav {
  position: fixed;
  left: 0;
  top: 0;
  bottom: 0;
  background: #333;
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 6rem;
}
.nav__logo {
  margin: 5rem auto;
}

.nav__image {
  width: 5rem;
  height: 5rem;
}

.nav__menu {
  color: #fff;
}

.menu__list {
  list-style: none;
  padding: 0;
}

.menu__item {
  background: #222;
  padding: 0.5rem 0.5rem;
  text-align: center;
  margin: 5px auto;
  cursor: pointer;
}
</style>
