<template>
  <div class="about d-flex justify-content-center align-items-center">
      <img src="https://static.vecteezy.com/system/resources/previews/011/153/370/original/3d-web-development-illustration-png.png">
      <div class="textcenter">
      	<h1 class="text-white">About Me</h1>
      	<h3>Front-End Developer</h3>
      	<p>
          I work as a web developer.  I believe I am a very ambitious person who loves to work on making the website work well. Working on the web is my passion as I love to work on exciting projects<br>
          Adept at identifying opportunities to enhance front-end design and improve the user experience.
        </p>
      </div>
  </div>
  
</template>

<style scoped>
  .about{
    height: 600px
  }
  img{
  	width: 400px
  }
  @media only screen and (max-width: 600px){
    .about{
      height: auto;
      flex-direction: column;
    }
    img{
      width: 100%;
    }
    .textcenter{
      text-align: center;
    }
  }
</style>
