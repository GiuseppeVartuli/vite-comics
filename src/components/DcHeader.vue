<script>
export default {
  name: "DcHeader",
};
</script>

<template>
  <header>
    <nav>
      <div class="logo">
        <img class="logo_top" src="../assets/img/dc-logo.png" alt="logo_dc" />
      </div>
      <div class="menu">
        <ul>
          <li><a href="#">CHARACTERS</a></li>
          <li><a href="#">COMICS</a></li>
          <li><a href="#">MOVIES</a></li>
          <li><a href="#">TV</a></li>
          <li><a href="#">GAMES</a></li>
          <li><a href="#">COLLECTIBLES</a></li>
          <li><a href="#">VIDEOS</a></li>
          <li><a href="#">FANS</a></li>
          <li><a href="#">NEWS</a></li>
          <li><a href="#">SHOP</a></li>
        </ul>
      </div>
    </nav>
  </header>
</template>

<style>
header {
  height: 117px;
  width: 100%;
  background-color: rgb(250, 250, 250);
}
nav {
  padding: 19px 0;
  display: flex;
  justify-content: space-around;
  align-items: center;

  & ul {
    display: flex;
  }
  & li {
    list-style: none;
    padding: 15px;
  }
  & a {
    text-decoration: none;
    color: var(--dc-primary);
  }
}
.logo_top {
  width: 80px;
}
</style>
