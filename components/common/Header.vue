<template>
<div class="header">
  <div class="topHeader__left   ">
    <div class="navbar__left flex flex-row ">
      <div class="group__logo ">
        <img src="~assets/logo.png" alt="logo Tripath" />
      </div>
      <div class="group__menu ml-[72px] center  ">
        <div class="nav__items flex items-center text-[#AEAEB2] ">
          <div class="menuItem mr-[40px] text-[#003CF9] ">Home</div>
          <div class="menuItem mr-[40px] ">Find talent</div>
          <div class="menuItem mr-[40px]">My team</div>
          <div class="menuItem mr-[40px]">Support</div>
        </div>
      </div>
    </div>
  </div>
  <div class="topHeader__right float-right">
   <div class="flex">
     <button class=" text-white font-bold py-2 px-4 rounded">
       Register
     </button>
     <button class="bg-[#003CF9] hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
       Button
     </button>
   </div>
  </div>
</div>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>
.header{
  background-color: #1E1E1E;
  height: 80px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.center{
  width: 100%;
  align-items: center;
  justify-content: center;
}
</style>
