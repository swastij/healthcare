<template>
  <div class="nav-wrapper">
      <div id="navLeft" class="left">
          <div class="T-box">
          <div class="T">
            T
          </div>
          <div class="T-text">
          <p>Trafalgar</p>
          </div>
          </div>
      </div>
      <div class="right">
          <div class="right-items">
              <p>
              Home
              </p>
          </div>
          <div class="right-items">
              <p>
              Find a doctor
             </p>
          </div>
          <div class="right-items">
              <p>
              Apps
              </p>
          </div>
          <div class="right-items">
              <p>
              Testimonials
              </p>
          </div>  
          <div class="right-items">
              <p>
              About Us
              </p>
          </div>
      </div>

  </div>
    
</template>

<script>
export default {
  name: "Nav",

};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style >
.nav-wrapper{
    display: flex;
    /* flex-wrap: wrap; */
    justify-content: space-between;
    align-items: center;
    top: 0;
    padding: 2%;
    box-sizing: border-box;
}
.left{
    width:35%;   
}
#navLeft{
    margin: auto;
}
.right{
    width:60%;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;

}
.T-box{
    height: 40px;
    display: flex;
    align-items: center;
}
.T{
    width:40px;
    height: 40px;
    background-color: #458FF6;
    border-radius: 50%;
    color: #ffffff;
    position: absolute;
    display: flex;
    justify-content: center;
    align-items: center;
    
}
.T-text{
   margin-left: 48px;
}

.right-items > p{
    font-size: 24px;
    color: #233348;
    font-family: Mulish;
    color:darkgray;

}
.right-items > p:hover{
    color:#1F1534;

}

</style>
