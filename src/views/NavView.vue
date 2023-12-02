<script setup>
  function home() {
  window.scrollBy(0,0)
  }
   function about() {
    window.scrollBy(0,600)
    }
    function abouttab() {
    window.scrollBy(0,200)
    }
    function skill() {
    window.scrollBy(0,1200)
    }
     function contect() {
    window.scrollBy(0,1800)
    }
    function openNav() {
      document.getElementById("mySidenav").style.width = "60%";
    }

/* Set the width of the side navigation to 0 */
  function closeNav() {
    document.getElementById("mySidenav").style.width = "0";
   
   } 
</script>

<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-dark">
    <span class="w-50 fs-5 fst-italic text-white">Port Folio</span>
    <div class="w-50 d-flex justify-content-evenly">
         <router-link @click="home" class="routerlink" to="/">Home</router-link>
         <router-link @click="about" class="routerlink" to="/">About</router-link>
        <!--  <router-link class="routerlink " to="/services">Services</router-link>	 -->
         <router-link  @click="skill" class="routerlink" to="/">Skills</router-link>	
         <router-link @click="contect" class="routerlink" to="/">Contect</router-link>		 
    </div>
      
   </nav>
   
</template>
<style scoped>
  .justify-content-evenly{
     display: block;
  }
  .material-symbols-outlined{
    display: none;
  }
	span{
		padding-left: 10px !important;
		
	}
	.routerlink{
		color: white;
		 text-decoration: none;
		 /*font-size: 14px;*/
		 opacity: 0.7

	}
	.routerlink:hover{
		opacity: 1

	}
  
   @media only screen and (max-width: 600px){
      .material-symbols-outlined{
        display: block;
        padding-right: 20px;
        cursor: pointer;
      }
       .justify-content-evenly{
           display: none !important;
       }
       .fst-italic{
          width: 70% !important
       }
   }

</style>
