<template>
  <div class="articles-container">
      <div class="heading">

      </div>
      <div class="rectangle"></div>
      <div class="column-container">
          <div class="column">
              <div class="column-img">
                  <img src="../assets/img/articles1.svg">
              </div>
              <div class="col-title">
                  <h3>
                  Disease detection, check up in the laboratory
                  </h3>
              </div>
              <div class="col-desc"> <h5> In this case, the role of the health laboratory is very important to do a disease detection...</h5> </div>
              <div class="read-more">
                  <a href="">Read more -
                      <i class="arrow right-arrow"></i>
                  </a>
              </div>
          </div>
          <div class="column">
              <div class="column-img">
                  <img src="../assets/img/articles2.svg">
              </div>
              <div class="col-title">
                  <h3>
                  Herbal medicines that are safe for consumption
                  </h3>
              </div>
              <div class="col-desc"> <h5> Herbal medicine is very widely used at this time because of its very good for your health...</h5></div>
              <div class="read-more">
                  <a href="">Read more -
                      <i class="arrow right-arrow"></i>
                  </a>
              </div>

          </div>
          <div class="column">
              <div class="column-img">
                  <img src="../assets/img/articles3.svg">
              </div>
              <div class="col-title">
                  <h3>
                  Natural care for healthy facial skin
                  </h3>
              </div>
      
              <div class="col-desc"> <h5> A healthy lifestyle should start from now and also for your skin health. There are some...</h5></div>
              <div class="read-more">
                  <a href="">Read more -
                      <i class="arrow right-arrow"></i>
                  </a>
              </div>

          </div>

      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.column-img{
    width: 100%;
}
.column-img>img{
    width:100%;
}

.right-arrow{
  transform: rotate(-45deg);
  -webkit-transform: rotate(-45deg);

}
.read-more>a{
    color: #458ff6;
    text-decoration: none;
}
</style>