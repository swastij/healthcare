<template>
  <div class="leading-container">
    <div class="left-box">
      <div class="heading">
        <h3>Leading healthcare providers</h3>
      </div>
      <div class="rectangle"></div>
      <div class="description">
        <h5>
          Trafalgar provides progressive, and affordable healthcare, accessible
          on mobile and online for everyone. To us, it’s not just work. We take
          pride in the solutions we deliver
        </h5>
      </div>
      <div class="learn-more">
        <button id="leadingBtn">Learn more</button>
      </div>
    </div>
    <div class="right-box">
      <div class="leading-img">
        <img src="../assets/img/leading.svg" />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.leading-container {
  width: 100%;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    /* justify-content: center;
    /* align-items: center; */
}
.left-box {
  width: 40%;
}
.right-box {
  width: 40%;
}
/* .heading{
    width: 100%;
} */
.heading > h3 {
  font-size: 36px;
  line-height: 56px;
}
/* .description{
    width:100%;
} */
.description > h5 {
  color: #7d7987;
  font-size: 18px;
  line-height: 30px;
}
#leadingBtn{
    width:50%;
}
.leading-img {
  width: 100%;
}
.leading-img>img {
  width: 100%;
}
</style>