<template>
<div class="footer__page">
  <div class="footer__contact pt-[120px]">
    <div class="content__footer flex justify-center ">
      <div class="item-content">
        <p class="font-normal text-[#8C8C8C] px-[60px]">About us</p>
      </div>
      <div class="item-content">
        <p class="font-normal text-[#8C8C8C] px-[60px]" >IT Viec</p>
      </div>
      <div class="item-content">
        <p class="font-normal text-[#8C8C8C] px-[60px]">Top Dev</p>
      </div>
      <div class="item-content">
        <p class="font-normal text-[#8C8C8C] px-[60px]">Contact</p>
      </div>
      <div class="item-content">
        <p class="font-normal text-[#8C8C8C] px-[60px]">Privacy policy</p>
      </div>
      <div class="item-content">
        <p class="font-normal text-[#8C8C8C] px-[60px]">Terms of Use</p>
      </div>
    </div>
  </div>
  <div class="footer__since flex justify-between pt-[40px] pb-[40px]">
    <div class="footer__logo">
      <img src="~assets/logo.png" alt="logo Tripath" />
    </div>
    <div class="footer__year">
      <span class="text-[#8C8C8C] ">© 2000-2021, All Rights Reserved</span>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped>
.footer__page{
  display: flex;
  flex-direction: column;
}
</style>
