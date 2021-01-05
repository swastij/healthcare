<template>
  <div class="download-container">
    <div class="left-box">
        <div class="leading-img">
        <img src="../assets/img/download.svg" />
      </div>
    </div>
    <div class="right-box">
      <div class="heading">
        <h3>Download our mobile apps</h3>
      </div>
      <div class="rectangle"></div>
      <div class="description">
        <h5>
          Our dedicated patient engagement app and web portal allow you to access information instantaneously (no tedeous form, long calls, or administrative hassle) and securely
        </h5>
      </div>
      <div class="learn-more">
        <button id="leadingBtn">Download
          <i class="arrow down"></i>
          
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.download-container {
  width: 100%;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    /* justify-content: center;
    /* align-items: center; */
}
.arrow {
  border: solid   #458ff6;
  border-width: 0 2px 2px 0;
  display: inline-block;
  padding: 3px;
}
.down {
  transform: rotate(45deg);
  -webkit-transform: rotate(45deg);
}
</style>