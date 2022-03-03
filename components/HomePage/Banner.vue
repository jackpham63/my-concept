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
     <div class="logo__company">
       <img class="banner-logo" alt="logo-01" src="~assets/banner01.png">
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

}
.logo__company {

}
</style>
