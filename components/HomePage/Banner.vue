<template>
 <div>
   <div class="banner-row">
     <div class="flex-1">
       <img class="makeBright-img" alt="make br" src="~assets/makeBright.png">
       <button class="btnGet bg-[#003CF9] hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
         Get Started
       </button>
     </div>
     <div>
       <img class="banner-img" alt="banner" src="~assets/banner.png">
     </div>
   </div>
   <div class="logos">
     <div class="logo__card">
       <img class="banner-logo" alt="logo-01" src="~assets/banner01.png">
     </div>
     <div class="logo__card">
       <img class="banner-logo" alt="logo-01" src="~assets/banner02.png">
     </div>
     <div class="logo__card">
       <img class="banner-logo" alt="logo-01" src="~assets/banner03.png">
     </div>
     <div class="logo__card">
       <img class="banner-logo" alt="logo-01" src="~assets/banner04.png">
     </div>
     <div class="logo__card">
       <img class="banner-logo" alt="logo-01" src="~assets/banner05.png">
     </div>
     <div class="logo__card">
       <img class="banner-logo" alt="logo-01" src="~assets/banner06.png">
     </div>
     <div class="logo__card">
       <img class="banner-logo" alt="logo-01" src="~assets/banner07.png">
     </div>
     <div class="logo__card">
       <img class="banner-logo" alt="logo-01" src="~assets/banner08.png">
     </div>
     <div class="logo__card">
       <img class="banner-logo" alt="logo-01" src="~assets/banner09.png">
     </div>
     <div class="logo__card">
       <img class="banner-logo" alt="logo-01" src="~assets/banner10.png">
     </div>
     <div class="logo__card">
       <img class="banner-logo" alt="logo-01" src="~assets/banner11.png">
     </div>
     <div class="logo__card">
       <img class="banner-logo" alt="logo-01" src="~assets/banner12.png">
     </div>
     <div class="logo__card">
       <img class="banner-logo" alt="logo-01" src="~assets/banner13.png">
     </div>
     <div class="logo__card">
       <img class="banner-logo" alt="logo-01" src="~assets/banner14.png">
     </div>
   </div>

 </div>
</template>

<script>
export default {
  name: "Banner"
}
</script>

<style scoped>
.banner-row {
  display: flex;
  align-items: center;
  color: white;
  margin-top: 100px;
}
.banner-img {
  width: 565px;
  height: 265px;
}
.makeBright-img{
  width: 553px;
  height: 215px;
}
.btnGet{
  width: 82px;
  height: 21px;
}
.logos{
  display: flex;
  flex-wrap: wrap;
  margin-top: 133px;
  margin-bottom: 100px;
  margin-left: -20px;
}
.logo__card {
  width: calc(12% - 20px);
  margin-left: 20px;
}
</style>
