<template>
  <header class="container">
      <div class="header-sx">
          <img src="../assets/img/dc-logo.png" alt="logo-dc">
      </div>
      <div class="header-dx">
          <ul>
              <li> <a href="">characters</a></li>
              <li> <a href="">comics</a></li>
              <li> <a href="">movies</a></li>
              <li> <a href="">tv</a></li>
              <li> <a href="">games</a></li>
              <li> <a href="">collectibles</a></li>
              <li> <a href="">videos</a></li>
              <li> <a href="">fans</a></li>
              <li> <a href="">news</a></li>
              <li> <a href="">shop</a></li>
          </ul>
      </div>
  </header>
</template>

<script>
export default {
}
</script>

<style lang="scss" scoped>
    header {
    display: flex;
    
    }
    ul {
        display: flex;
        li {
            list-style-type: none;
            margin: 0 1em;
            justify-content: end;
            justify-items: center;
            a {
                text-decoration: none;
                text-transform: uppercase;
            }
        }
    }
</style>