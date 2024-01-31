<script>
export default {
  name: "AppHeader",
};
</script>

<template>
  <header>
    <div class="container d-flex justify-between align-items-center">
      <div class="logo">
        <img src="/src/assets/img/dc-logo.png" alt="logo" />
      </div>

      <div class="menu">
        <ul class="d-flex">
          <li><a href="#">Characters</a></li>
          <li>
            <a href="#" class="active">Comics</a>
            <div class="underline"></div>
          </li>
          <li><a href="#">Movies</a></li>
          <li><a href="#">TV</a></li>
          <li><a href="#">Games</a></li>
          <li><a href="#">Collectibles</a></li>
          <li><a href="#">Videos</a></li>
          <li><a href="#">Fans</a></li>
          <li><a href="#">News</a></li>
          <li><a href="#">Shop</a></li>
        </ul>
      </div>
    </div>
  </header>
</template>

<style scoped>
header {
  background: var(--dc-comics-light);
}

li {
  position: relative;
  padding-block: 52px;
  text-transform: uppercase;
  font-weight: 700;
  margin-inline: 17px;

  a {
    font-size: 14px;
    color: var(--dc-comics-dark);
  }
}

.active {
  color: var(--dc-comics-primary);
}

.underline {
  position: absolute;
  background: var(--dc-comics-primary);
  width: 100%;
  height: 5px;
  bottom: 0;
}
</style>
