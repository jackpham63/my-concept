<template>
<div>
  <div class="weDid">
    <p class="uppercase text-4xl mb-3 text-[#FFFFFF]"><span class="font-extrabold">WHAT </span>we did</p>
    <p class="text-[#AEAEB2]">Industries & Skill sets</p>
  </div>
  <div class="weDidContent mt-10">
    <div class="did-left flex-1 flex ">
      <div class="skill__left flex-1">
        <div class="skill__text border-l-[5px] border-[#003CF9] mb-4">
          <p class="text__p pl-2">Media and Entertainment</p>
        </div>
        <p class="text01 mb-4">
          We develop next-gen media and entertainment app & web solutions using leading edge technologies that support cross-platform compatibilities.
        </p>
        <div class="skill__text border-l-[5px] border-[#003CF9]">
          <p class="text__p pl-2">Telecom and Network</p>
        </div>
      </div>
      <div class="skill__right flex-1">
        <div class="skill__text border-l-[5px] border-[#003CF9] mb-4">
          <p class="text__p pl-2">Media and Entertainment</p>
        </div>
        <div class="skill__text border-l-[5px] border-[#003CF9] mb-4">
          <p class="text__p pl-2">E-commerce and <br> Distribution</p>
        </div>

        <div class="skill__text border-l-[5px] border-[#003CF9] mb-4">
          <p class="text__p pl-2">Fintech</p>
        </div>
      </div>
    </div>
    <div class="did-right">
      <div class="picSmall">
        <img class="" alt="pic small" src="~assets/picSmall.png">
      </div>
      <div class="picLarge">
        <img class="" alt="pic large" src="~assets/picLarge.png">
      </div>
    </div>
  </div>
  <div class="weDidBottom mt-10 rounded-2xl flex  justify-center flex-col px-7">
    <div>
      <p class="text01 font-bold text-2xl">Statup GG</p>
    </div>
    <div>
      <p class="text01 text-lg font-medium	" > An AI virtual assistant desktop application provide related information that will help League of Legends players increase their win rate while playing the game.</p>
    </div>
     </div>
</div>
</template>

<script>
export default {
  name: "WeDid"
}
</script>
<style scoped>
.weDidContent{
  display: flex;
  flex-direction: row;
}
.did-right{
  width: 512px;
  position: relative;
}
.picLarge{
  margin-top: 20px;
  margin-left: 30px;
}
.picSmall{
  width: 3079px;
  height: 181px;
  position: absolute;
  margin-top: 170px;
}
.skill__left, .skill__right{
  flex: 1
}
.text__p{
  color: #FFFFFF;
}
.text01{
  color: #FFFFFF;
}
.weDidBottom{
  width: 1170px;
  height: 141px;
  background: #2C2C2E;
;
}
</style>
