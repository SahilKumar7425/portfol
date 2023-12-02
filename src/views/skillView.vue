<template>
  <div class="skill">
  <div class="d-flex justify-content-center">
     <h1 class="text-white">My Skills</h1>
  </div>
 
  <div class="about d-flex justify-content-evenly align-items-center flex-wrap">
      <div class="containerdiv" style="margin-top:50px">
        <span>HTML</span>
        <div class="innerdiv" style="width:210px;background-color:gray;height:5px;border-radius:5px"><p style="width:90%;background-color:red;height: 5px;border-radius:5px"></p></div>
      </div>
        <div class="containerdiv" style="margin-top:50px">
        <span>CSS</span>
        <div class="innerdiv" style="width:210px;background-color:gray;height:5px;border-radius:5px"><p style="width:80%;background-color:blue;height: 5px;border-radius:5px"></p></div>
      </div>
      <div class="containerdiv" style="margin-top:50px">
      <span>JavaScript</span>
        <div class="innerdiv" style="width:210px;background-color:gray;height:5px;border-radius:5px"><p style="width:75%;background-color:orange;height: 5px;border-radius:5px"></p></div>
      </div>
      <div class="containerdiv" style="margin-top:50px">
      <span>Jquery</span>
        <div class="innerdiv" style="width:210px;background-color:gray;height:5px;border-radius:5px"><p style="width:80%;background-color:#8A2BE2;height: 5px;border-radius:5px"></p></div>
      </div>
      <div class="containerdiv" style="margin-top:50px">
       <span>ReactJs</span>
        <div class="innerdiv" style="width:210px;background-color:gray;height:5px;border-radius:5px"><p style="width:85%;background-color:#ADD8E6;height: 5px;border-radius:5px"></p></div>
      </div>
       <div class="containerdiv" style="margin-top:50px">
       <span>Redux</span>
        <div class="innerdiv" style="width:210px;background-color:gray;height:5px;border-radius:5px"><p style="width:90%;background-color:yellow;height: 5px;border-radius:5px"></p></div>
      </div>
       <div class="containerdiv" style="margin-top:50px">
       <span>Bootstrap</span>
        <div class="innerdiv" style="width:210px;background-color:gray;height:5px;border-radius:5px"><p style="width:95%;background-color:orange;height: 5px;border-radius:5px"></p></div>
      </div>
       <div class="containerdiv" style="margin-top:50px">
       <span>VueJs</span>
        <div class="innerdiv" style="width:210px;background-color:gray;height:5px;border-radius:5px"><p style="width:80%;background-color:#CD5C5C;height: 5px;border-radius:5px"></p></div>
      </div>
       <div class="containerdiv" style="margin-top:50px">
       <span>Vuetify</span>
        <div class="innerdiv" style="width:210px;background-color:gray;height:5px;border-radius:5px"><p style="width:70%;background-color:#ADFF2F;height: 5px;border-radius:5px"></p></div>
      </div>
       <div class="containerdiv" style="margin-top:50px">
       <span>Ajax</span>
        <div class="innerdiv" style="width:210px;background-color:gray;height:5px;border-radius:5px"><p style="width:75%;background-color:#FFB6C1;height: 5px;border-radius:5px"></p></div>
      </div>
       <div class="containerdiv" style="margin-top:50px">
       <span>Vuex</span>
        <div class="innerdiv" style="width:210px;background-color:gray;height:5px;border-radius:5px"><p style="width:80%;background-color:#3CB371;height: 5px;border-radius:5px"></p></div>
      </div>
      <div class="containerdiv" style="margin-top:50px">
       <span>Git/Github</span>
        <div class="innerdiv" style="width:210px;background-color:gray;height:5px;border-radius:5px"><p style="width:70%;background-color:blue;height: 5px;border-radius:5px"></p></div>
      </div>
  </div>
  </div>
</template>

<style scoped>
 .skill{
  height: 600px;
 }
  @media only screen and (max-width: 600px){
    .about{
       height: auto;
    }
    .skill{
      height: auto;
    }
    .containerdiv{
      margin-top: 10px !important;
      width: 80%
    }
    .innerdiv{
       width: 100% !important;
    }
  }
</style>
