<template>
  <div class="footer-container">
      <div class="left-footer">
          <div class="left">
          <div class="T-box">
          <div class="T">
            T
          </div>
          <div class="T-text">
          <p>Trafalgar</p>
          </div>
          </div>
          <div class="footer-desc">
          <h5>Trafalgar provides progressive, and affordable healthcare, accessible on mobile and online for everyone</h5>
      </div>
      <div class="footer-copyright">©Trafalgar PTY LTD 2020. All rights reserved</div>
      </div>
      </div>
      
      <div class="right-footer">
          <div class="right-col">
              <h3>Company</h3>
              <h5>About</h5>
              <h5>Testimonials</h5>
              <h5>Find a doctor</h5>
              <h5>Apps</h5>
          </div>
          <div class="right-col">
              <h3>Region</h3>
              <h5>Indonesia</h5>
              <h5>Singapore</h5>
              <h5>Canada</h5>
              <h5>Hongkong</h5>
          </div>
          <div class="right-col">
              <h3>Help</h3>
              <h5>Help Center</h5>
              <h5>Contact Support</h5>
              <h5>Instructions</h5>
              <h5>How it works</h5>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.footer-container{
    background-image: linear-gradient( #67C3F3, #5A98F2);
    position: absolute;
    width: 100% ;
    display: flex;
    margin-top:2%;
    box-sizing: border-box;
    padding: 2%;
    left: 0;
}
.footer-desc, .footer-copyright{
    margin-top:6%;
}
.left-footer{
    width:30%;
    color: white;
    margin: auto;

}
.right-footer{
    width:60%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: auto;
    color: #ffffff;
}
.right-col{
    width:33%;
}
</style>