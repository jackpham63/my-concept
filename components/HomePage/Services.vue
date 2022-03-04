<template>
  <div class="services">
    <div class="ourServices">
      <p class="uppercase text-4xl mb-3 text-[#FFFFFF]">
        <span class="font-extrabold">Our</span>included services.
      </p>
      <p class="text-[#AEAEB2]">
        We help client to create value with our talented expert.
      </p>
    </div>
    <div class="mt-10 services__content">
      <div class="mr-7 services__card rounded-2xl">
       <div class="card__wrap m-6">
         <div class="icon__services">
           <img class="" alt="icon-01" src="~assets/icon-services01.png" />
         </div>
         <div class="title__services">
           <h1 class="my-3 uppercase text-[#FFFFFF] text-lg font-bold">
             Full cycle software development
           </h1>
         </div>
         <div class="content__services">
           <p class="text-[#AEAEB2]">
             We provide full-cycle software development services which help you
             simply focus on your core business. We will handle the entire
             development process: Business analysis, architecture, UX design,
             development, and QA.
           </p>
         </div>
       </div>
      </div>
      <div class="mr-7 services__card rounded-2xl">
        <div class="card__wrap  m-6">
          <div class="icon__services">
            <img class="" alt="icon-02" src="~assets/icon-services02.png" />
          </div>
          <div class="title__services">
            <h1 class="my-3 uppercase text-[#FFFFFF] text-lg font-bold">
              IT Consulting
            </h1>
          </div>
          <div class="content__services">
            <p class="text-[#AEAEB2]">
              We provide full-cycle software development services which help you
              simply focus on your core business. We will handle the entire
              development process: Business analysis, architecture, UX design,
              development, and QA.
            </p>
          </div>
        </div>
      </div>
      <div class="mr-7 services__card rounded-2xl">
        <div class="card__wrap  m-6">
          <div class="icon__services">
            <img class="" alt="icon-03" src="~assets/icon-services03.png" />
          </div>
          <div class="title__services">
            <h1 class="my-3 uppercase text-[#FFFFFF] text-lg font-bold">
              Dedicated Development Team
            </h1>
          </div>
          <div class="content__services">
            <p class="text-[#AEAEB2]">
              If you need skillful programmers for a project but don’t want to
              waste time and resources on recruitment and HR management, our
              dedicated team is specially selected to match your needs.
            </p>
          </div>
        </div>
      </div>
      <div class="mr-7 services__card rounded-2xl">
        <div class="card__wrap  m-6">
          <div class="icon__services">
            <img class="" alt="icon-04" src="~assets/icon-services04.png" />
          </div>
          <div class="title__services">
            <h1 class="my-3 uppercase text-[#FFFFFF] text-lg font-bold">
              Cloud & DevOps
            </h1>
          </div>
          <div class="content__services">
            <p class="text-[#AEAEB2]">
              We use our expertise in cloud and server solutions to derive and
              build high-performing environments that helps you cut down cloud
              spending, automate infrastructure monitoring, and increase
              architectural flexibility.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Services",
};
</script>

<style scoped>
.icon__services{
  width: 50px;
  height: 50px;
}
.title__services{
  width: 221px;
  height: 54px;
  margin-bottom: 20px;
}
.services {
  margin-bottom: 124px;
}
.services__content {
  display: flex;
}
.services__card{
  width: 269px;
  height: 370px;
}
.services__card:nth-child(2n+1){
  background-color: #2C2C2E;

}
.services__card:nth-child(2n+2){
  background-color: #000000;
}
</style>
