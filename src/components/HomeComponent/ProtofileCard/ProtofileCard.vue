<template>
  <div class="card d-flex flex-lg-row flex-column p-3 shadow coko">
    <div class="line"></div>
    <div class="card-body text-left w-25 hehe px-3 pt-2 pb-2">
      <h5 class="card-title bone" id="protofilehead">Portfolio</h5>
      <p class="card-text hhee">
        I had made some responsive webpage with nice desgin ..... i will happy if you
        see them
      </p>
      <router-link to="/protofile" class="btn btn-primary mt-sm-5 shadow" id="bto-tog"
        >Show Protofile</router-link
      >
    </div>
    <div class="hgho">
    <div class="card mr-2 togglee h-100" style="width: 13rem;">
      <div class="bbo">
        <p class="bbo-info">Rock , Paper and Scissors Game</p>
        <button class="btn btn-primary bto shadow" id="bto-tog" @click="opentap('https://rock-paper-scissors-master-lyart.vercel.app/')">Visit</button>
      </div>
      <img src="./../../../assets/project17.jpg" class="card-img-top" alt="project1" />
      <div class="card-body">
        <p class="card-text titlee text-left">
          <span class="mr-2 htmc">HTMl</span>
          <span class="mr-2 cssc">CSS</span>
          <span class="mr-2 jsc">JS</span>
        </p>
      </div>
    </div>
    </div>
    <div class="hgho">
    <div class="card mr-2 togglee h-100" style="width: 13rem;">
      <div class="bbo">
        <p class="bbo-info">Where in the world</p>
        <a class="btn btn-primary bto shadow" id="bto-tog" @click="opentap('https://rest-countries-api-with-color-theme-switcher-master-rho.vercel.app/#')">Visit</a>
      </div>
      <img src="./../../../assets/project15.jpg" class="card-img-top" alt="project2" />
      <div class="card-body">
        <p class="card-text titlee text-left">
          <span class="mr-2 htmc">HTMl</span>
          <span class="mr-2 cssc">CSS</span>
          
        </p>
      </div>
    </div>
  </div>
    <div class="hgho">
    <div class="card togglee h-100" style="width: 13rem;">
      <div class="bbo">
        <p class="bbo-info">Todo App</p>
        <button class="btn btn-primary bto shadow" id="bto-tog" @click="opentap('https://todo-app-lake.vercel.app/')">Visit</button>
      </div>
      <img src="./../../../assets/project14.jpg" class="card-img-top" alt="project2" />
      <div class="card-body">
        <p class="card-text titlee text-left">
          <span class="mr-2 htmc">HTMl</span>
          <span class="mr-2 cssc">CSS</span>
          <span class="mr-2 jsc">JS</span>
        </p>
      </div>
    </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "ProtofileCard",
  methods:{
    opentap(v){
      window.open(v,"_blank");
    }
  }
};
</script>
<style lang="scss">
@import 'ProtofileCard' ;
</style>
