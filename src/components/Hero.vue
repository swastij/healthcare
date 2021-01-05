<template>
  <div class="hero-container">
    <div class="text">
      <div class="heading">
        <h2>Virtual healthcare for you</h2>
      </div>
      <div class="desc">
        <h3>
          Trafalgar provides progressive, and affordable healthcare, accessible
          on mobile and online for everyone
        </h3>
      </div>
      <div class="btn">
        <button>Consult today</button>
      </div>
    </div>
    <div class="image">
      <img src="../assets/img/hero-img.svg" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hero-container {
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  overflow-x: hidden;
  height: 597.17px;
  overflow-y: hidden;

}
.text {
  width: 40%;
}
.image {
      right: 0;
    /* height: 390.17px; */
    position: absolute;
  width: 50%;

}
.img{
    width: auto;
    height: 597.17px;
}
.heading > h2 {
  font-size: 48px;
}
.desc {
  margin-top: 20px;
}
.desc > h3 {
  color: #7d7987;
}

.btn > button {
  background-color: #458ff6;
  border-radius: 40px;
  border-style: none;
  color: #ffffff;
  width: 32%;
  height: 48px;
  margin: auto;
  margin-top: 36px;
}
/* .heading>h2{
  font-size: 48px;
} */
</style>
