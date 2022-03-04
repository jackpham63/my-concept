<template>
<div class="whoAreWe">
  <div class="contentWho">
    <p class="uppercase text-4xl mb-3 "><span class="font-extrabold">WHO</span> ARE WE</p>
    <p class="text-[#AEAEB2]">Founded in 2006, Tripath offers first-class software services for hundreds of global clients. We develop the most cutting-edge and creative products that provide comprehensive solutions for business. We listen to specific problems, needs, and wants of our clients and support them throughout the whole way, from an idea to implementation.
    </p>
  </div>
<div class="bgIntro">
  <div class="intro">
    <div class="intro__card__wrap">
      <div class="intro__card ">
        <img class="intro__img" alt="intro 01" src="~assets/unplash02.png">
      </div>
    </div>
    <div class="intro__card__wrap">
    <div class="intro__card bg-[#10C4D3] text-[#F2F2F7] pt-[16px] px-[16px] ">
      <div class="text__top ">
        <h1>15 +</h1>
        <p>Years of outsourcing experience</p>
      </div>
      <div class="text__bottom">
        <img class="" alt="intro 01" src="~assets/services-bottom12.png">
      </div>
    </div>
    </div>
    <div class="intro__card__wrap">
    <div class="intro__card">
      <img class="intro__img" alt="intro 01" src="~assets/unplash03.png">
    </div>
    </div>
    <div class="intro__card__wrap">
      <div class="intro__card bg-[#003CF9]">
        <div class="text__top text-[#F2F2F7] pt-[16px] px-[16px]">
          <h1>15 +</h1>
          <p>Years of outsourcing experience</p>
        </div>
        <div class="text__bottom">
          <img class="" alt="intro 01" src="~assets/services-bottom12.png">
        </div>
      </div>
    </div>
    <div class="intro__card__wrap"><div class="intro__card">
      <img class="intro__img" alt="intro 01" src="~assets/unplash04.png">
    </div></div>
    <div class="intro__card__wrap"><div class="intro__card bg-[#2C2C2E]">
      <div class="text__top text-[#F2F2F7] pt-[16px] px-[16px]">
        <h1>15 +</h1>
        <p>Years of outsourcing experience</p>
      </div>
      <div class="text__bottom">
        <img class="" alt="intro 01" src="~assets/services-bottom3.png">
      </div>

    </div></div>
    <div class="intro__card__wrap"><div class="intro__card">
      <img class="intro__img" alt="intro 01" src="~assets/unplash01.png">
    </div></div>
    <div class="intro__card__wrap"><div class="intro__card bg-[#000000]">
      <div class="text__top text-[#F2F2F7] pt-[16px] px-[16px]">
        <h1>15 +</h1>
        <p>Years of outsourcing experience</p>
      </div>
      <div class="text__bottom">
        <img class="" alt="intro 01" src="~assets/services-bottom4.png">
      </div>
    </div></div>
  </div>
<!--  <div class="flex overflow-x-auto" v-if="false">
    <div v-for="slide in 5">
      <div v-for="item in slide.items">
        <div class="w-[100px] flex-1 mb-2">
          <img class="w-full" src="#" alt="image" />
        </div>
        <div class="">
          content
        </div>
      </div>
    </div>
  </div>-->
</div>
</div>
</template>
<script>
export default {
  name: "WhoAreWe"
}
</script>

<style scoped>
.whoAreWe{
  margin-bottom: 124px;
}
.contentWho{
  color: #FFFFFF
}
.bgIntro{
  height: 500px;
}
.intro{
  display: flex;
  overflow-x: auto;
  padding: 20px 0;
}
.intro__card{
  width: 100%;
  height: 100%;
  position: relative;
}
.intro__card img {
  width: 100%;
  height: 100%;
}
.text__bottom {
  position: absolute;
  left: 16px;
  bottom: 16px;
}
.text__bottom img {
  width: 32px;
  height: 32px;
}
.intro__card__wrap {
  width: 170px;
  min-width: 170px;
  height: 426px;
  margin-right: 16px;
}
.intro__card__wrap:nth-child(3n +1) {
  margin-top: 0;
}
.intro__card__wrap:nth-child(3n + 2) {
  margin-top: 35px;
}
.intro__card__wrap:nth-child(3n) {
  margin-top: 70px;
}
</style>
