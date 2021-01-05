<template>
  <div class="services-container">
    <div class="our-services">
      <div class="services-head">
        <h2>Our Services</h2>
      </div>
      <div class="rectangle"></div>
      <div class="services-desc">
        <p>
          We provide to you the best choiches for you. Adjust it to your health
          needs and make sure your undergo treatment with our highly qualified
          doctors you can consult with us which type of service is suitable for
          your health
        </p>
      </div>
    </div>
    <div class="column-container">
     
      <div class="column">
        <div class="col-img">
          <img src="../assets/img/search.svg" />
        </div>
        <div class="col-title">
          <h3>Search doctor</h3>
        </div>
        <div class="col-desc">
          <h5>
            Choose your doctor from thousands of specialist, general, and
            trusted hospitals
          </h5>
        </div>
      </div>
      <div class="column">
        <div class="col-img">
          <img src="../assets/img/pharmacy.svg" />
        </div>
        <div class="col-title">
          <h3>Online pharmacy</h3>
        </div>
        <div class="col-desc">
          <h5>
            Buy your medicines with our mobile application with a simple
            delivery system
          </h5>
        </div>
      </div>
      <div class="column">
        <div class="col-img">
          <img src="../assets/img/consultation.svg" />
        </div>
        <div class="col-title">
          <h3>Consultation</h3>
        </div>
        <div class="col-desc">
          <h5>
            Free consultation with our trusted doctors and get the best
            recomendations
          </h5>
        </div>
      </div>
      <div class="column">
        <div class="col-img">
          <img src="../assets/img/details.svg" />
        </div>
        <div class="col-title">
          <h3>Details info</h3>
        </div>
        <div class="col-desc">
          <h5>
            Free consultation with our trusted doctors and get the best
            recomendations
          </h5>
        </div>
      </div>
      <div class="column">
        <div class="col-img">
          <img src="../assets/img/emergency.svg" />
        </div>
        <div class="col-title">
          <h3>Emergency care</h3>
        </div>
        <div class="col-desc">
          <h5>
            You can get 24/7 urgent care for yourself or your children and your
            lovely family
          </h5>
        </div>
      </div>
      <div class="column">
        <div class="col-img">
          <img src="../assets/img/tracking.svg" />
        </div>
        <div class="col-title">
          <h3>Tracking</h3>
        </div>
        <div class="col-desc">
          <h5>Track and save your medical history and health data</h5>
        </div>
      </div>
       <div class="column-bg">
        <img src="../assets/img/columnBg.svg" />
      </div>
      <div class="learn-more">
        <button>Learn more</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.services-container {
  width: 100%;
  margin-top: 16%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
}
.our-services {
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 80%;
}
.services-head {
  width: 100%;
}
.rectangle {
  margin: 2%;
  background-color: #000000;
  width: 56px;
  height: 2px;
}
.services-desc {
  width: 100%;
  /* margin-top: 4%; */
}
.column-container {
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  position: relative;
}
.column-bg {
  position: absolute;
  left: 0;
  z-index: 1;
  top: -180px;
 
  /* transform: rotate(10.46deg); */
}
.column-bg > img {
  width: 100%;
}

.dot-box {
  position: absolute;
  right: 0;
  top: 0.75;
  opacity: 0.3;
}
.column {
  border-radius: 8%;
  box-shadow: 5px 10px 18px #888888;
  width: 30%;
  margin-top: 4%;
  padding: 2%;
  box-sizing: border-box;
  z-index: 2;
}
.col-img {
  margin: 2% 0%;
}
.col-title {
  margin: 2% 0%;
}
.col-desc {
  margin: 2% 0%;
}
.col-desc>h5{
    color: #7D7987;
}
.learn-more {
  width: 100%;
  text-align: center;
}
.learn-more > button {
  background-color: white;
  border: 1.4px solid #458ff6;
  color: #458ff6;
  box-sizing: border-box;
  height:56px;
  width: 20%;
  border-radius: 55px;
  margin-top: 4%;
}
</style>