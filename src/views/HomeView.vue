
<script setup>
  import About from './AboutView.vue'
   import Skills from './skillView.vue'
   import Contect from './contectView.vue'
   
</script>

<template>
     <div class="homedivmain d-flex">
     	 <div class=" helosir">
     	 	<span class="fs-4 fw-bold text-gray">Hello, It's Me </span><br>
     	 	<span class="fs-1 fw-bold text-white">SAHIL KUMAR</span><br>
     	 	
     	 	<span>
     	 		And I'm a Front-End Developer, specializing<br> in UI
               design, web development, project management,
               and Java script
     	 	</span>
     	 </div>
     	 <div class="imgdiv">
     	 	<img class="fstimg" src="https://static.vecteezy.com/system/resources/previews/011/153/363/original/3d-web-developer-working-on-project-illustration-png.png">
     	 </div>
     </div>
     <About/>
     <br><br>
     <Skills/>
     <br><br>
     <Contect/>
     <br><br>
      
</template>
<style scoped>
	.homedivmain{
      height: 600px;
      display: flex;
      align-items: center;
      justify-content: center;
     
	}
	.fstimg{
		width: 480px;
		border-radius:20px;
	}
	.helosir{
       box-sizing: border-box;
       /*padding-right: 20px;*/
	}
  @media only screen and (max-width: 600px) {
  .homedivmain{
    height: auto;
    flex-direction: column-reverse;
    justify-content: center;

  }
  .fstimg{
    width: 100%
  }
  .imgdiv{
    text-align: center;
  }
  .helosir{
    text-align: center;
  }
}
</style>
