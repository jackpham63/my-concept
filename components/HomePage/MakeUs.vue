<template>
<div class="makeUs mb-20">
  <div class="makeUsDif mb-20">
    <p class="uppercase text-4xl mb-3 text-[#FFFFFF]"><span class="font-extrabold">WHAT</span>MAKES US DIFFERENT?</p>
    <p class="text-[#AEAEB2]">We code for you. We grow with you</p>
  </div>
  <div class="make__content">
    <div class="make__left">
      <img class="" alt="Make-Us" src="~assets/makeUs.png">
    </div>
    <div class="make__right rounded-2xl">
     <div class="make__top">
       <p class="text-4xl mb-4 text-[#FFFFFF]">
         Customer needs
       </p>
       <div class="txt mb-6"></div>
       <p class="text-[#AEAEB2]">
         With the demand and cost getting higher in today’s software development market, it makes sense to find other ways for launching new IT products faster, cheaper and better. Software outsourcing is considered as one of the most effective solutions that help many companies to succeed without losing the quality of development. Beside some common reasons for outsourcing like cost cutting, greater focus on core business, accessing to a larger pool of innovative talents, it is the strategic purpose of company aiming to introduce the product to a new market as the locals have a better insight into their market.
       </p>
     </div>
      <div class="make__top">
        <p class="text-4xl mb-4 text-[#FFFFFF]">
          Pain
        </p>
        <div class="txt mb-6"></div>
        <p class="text-[#AEAEB2]">
          However, to implement the goal, the business faces to some main pain points: Limited information in the new market; Lack of trust and concern about fake resumes and overstated capabilities; Language barrier and time zone; Intellectual property concern. </p>
      </div>
    </div>

  </div>
</div>
</template>

<script>
export default {
  name: "MakeUs"
}
</script>

<style scoped>
.makeUs{
  position: relative;

}
.make__left{
position: absolute;
  margin-top: 40px;
  width: 369px;
  height: 446px;
}
.make__right{
  margin-left: 284px;
  background-color: #2C2C2E;
  width: 885px;
  height: 510px;
}
.txt{
  width: 40px;
  height: 4px;
  background-color: #003CF9;
}
.make__right{
  padding: 49px 40px 112px 125px;
}
</style>
