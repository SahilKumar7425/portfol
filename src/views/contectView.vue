<template>
  <div class="contect">
	<div class="d-flex justify-content-center">
	 <h1 class="text-white">Contect Me</h1>
	</div>
	<div class="d-flex align-items-center justify-content-around">
    <img src="https://static.vecteezy.com/system/resources/thumbnails/018/842/789/small_2x/realistic-phone-call-button-hotline-and-call-center-icon-customer-support-service-3d-rendering-free-png.png">
    <div class="spandiv">
    	<span class="span"><span class="text-white">Mobile Number</span> : 7425828276</span><br><br>
    	<span class="span"><sapn class="text-white">Gmail</sapn> : sahiljangirhudia@gmail.com</span><br><br>
    	<span><span class="text-white">Linkedin Profile </span>: https://www.linkedin.com/in/sahil-kumar-aa4917283/</span><br><br>
    	<span><span class="text-white">Instagram Profile</span> : https://www.instagram.com/sahil_sharma7425/</span>
    </div>
    </div>
    </div>
</template>

<style scoped>
  img{
  	width: 200px
  }
  .contect{
    height: 400px
  }
   @media only screen and (max-width: 600px){
    .contect{
      height: auto;
      flex-direction: column;
    }
    .align-items-center{
      flex-direction: column;
    }
     img{
        width:80%
      }
      span{
        margin-top: 40px !important;
        /*background-color: blue !important*/
      }
      .spandiv{
        margin-top: 20px;
        text-align: center;
      }
      
   }
</style>

