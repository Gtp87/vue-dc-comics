<template>
<footer>
  <div class="footer-top">
    <div class="container">
      <ul>
          <li>
              <img src="../assets/img/buy-comics-digital-comics.png" alt="">
              <h4><a href="">digital comics</a></h4>
          </li>
          <li>
              <img src="../assets/img/buy-comics-merchandise.png" alt="">
              <h4><a href="">dc merchandise</a></h4>
          </li>
          <li>
              <img src="../assets/img/buy-comics-subscriptions.png" alt="">
              <h4><a href="">subscription</a></h4>
          </li>
          <li>
              <img src="../assets/img/buy-comics-shop-locator.png" alt="">
              <h4><a href="">comic shop locator</a></h4>
          </li>
          <li>
              <img src="../assets/img/buy-dc-power-visa.svg" alt="">
              <h4><a href="">dc power visa</a></h4>
          </li>
      </ul>
    </div>
  </div>
  <div class="footer-center">
    <div class="container">
      <div class="background-logo clearfix">
        <div class="first-col">
          <h3>dc comics</h3>
            <ul>
              <li><a>Characters</a></li>
              <li><a>Comics</a></li>
              <li><a>Movies</a></li>
              <li><a>TV</a></li>
              <li><a>Games</a></li>
              <li><a>Videos</a></li>
              <li><a>News</a></li>
            </ul>
          <h3>shop</h3>
            <ul>
                <li><a>Shop DC</a></li>
                <li><a>Shop DC Collectibles</a></li>
            </ul>
        </div>
        <div class="second-col">
          <h3>dc</h3>
            <ul>
              <li><a>Terms Of Use</a></li>
              <li><a>Privacy policy (New)</a></li>
              <li><a>Ad Choiches</a></li>
              <li><a>Advertising</a></li>
              <li><a>Jobs</a></li>
              <li><a>Subscriptions</a></li>
              <li><a>Talent Workshops</a></li>
              <li><a>CPSC Certificates</a></li>
              <li><a>Ratings</a></li>
              <li><a>Shop Help</a></li>
              <li><a>Contact Us</a></li>
            </ul>
        </div>
        <div class="third-col">
          <h3>sites</h3>
            <ul>
              <li><a>DC</a></li>
              <li><a>MAD Magazine</a></li>
              <li><a>DC Kids</a></li>
              <li><a>DC Universe</a></li>
              <li><a>DC Power Visa</a></li>
            </ul>
        </div>
      </div>
        </div>
  </div>
  <div class="footer-bottom">
    <div class="container"></div>
  </div>
</footer>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style lang="scss" scoped>
  .footer-top {
  padding: 3em 0;
  background-color: #0282F9;
  ul {
    display: flex;
    justify-content: space-between;
    li {
      display: flex;
      align-items: center;
      list-style-type: none;
      img {
        width: 3em;
        margin: 0 1em;
      }
      a {
        text-decoration: none;
        text-transform: uppercase;
        color: white;
      }
    }
  }
}


  .footer-center {
    background-image: url(../assets/img/footer-bg.jpg);
    .container {
      .clearfix::after {
        content: "";
        clear: both;
        display: table;
      }
      .background-logo {
        padding: 2em 0 2em 0;
        background-image: url('../assets/img/dc-logo-bg.png');
        background-repeat: no-repeat;
        background-position-x: 100%;
        background-position-y: 50%;
        .first-col, .second-col, .third-col {
            float: left;
            width: 15%;
            h3 {
                text-transform: uppercase;
                padding: 0.8em 0;
                color: white;
            }
            ul {
                list-style: none;
                li {
                    padding-bottom: 0.5em;
                    font-size: 0.9em;
                    a {
                        text-decoration: none;
                        color: #959595;
                    }
                }
            }
        }
              
      }
          
    }
  }
</style>