<template>
<div class="services">
  <div class="ourServices">
    <h1>Our included services.</h1>
    <p>We help client to create value with our talented expert.</p>
  </div>
<div class="services__content">
  <div class="services__card">
    <div class="icon__services">
      <img class="" alt="icon-01" src="~assets/icon-services01.png">
    </div>
    <div class="title__services">
      <h1>Full cycle software development</h1>
    </div>
    <div class="content__services">
      <p>We provide full-cycle software development services which help you simply focus on your core business. We will handle the entire development process: Business analysis, architecture, UX design, development, and QA.</p>
    </div>
  </div>
  <div class="services__card">
    <div class="icon__services">
      <img class="" alt="icon-02" src="~assets/icon-services02.png">
    </div>
    <div class="title__services">
      <h1>IT Consulting</h1>
    </div>
    <div class="content__services">
      <p>We provide full-cycle software development services which help you simply focus on your core business. We will handle the entire development process: Business analysis, architecture, UX design, development, and QA.</p>
    </div>
  </div>
  <div class="services__card">
    <div class="icon__services">
      <img class="" alt="icon-03" src="~assets/icon-services03.png">
    </div>
    <div class="title__services">
      <h1>Dedicated Development Team</h1>
    </div>
    <div class="content__services">
      <p>If you need skillful programmers for a project but don’t want to waste time and resources on recruitment and HR management, our dedicated team is specially selected to match your needs.</p>
    </div>
  </div>
  <div class="services__card">
    <div class="icon__services">
      <img class="" alt="icon-04" src="~assets/icon-services04.png">
    </div>
    <div class="title__services">
      <h1>Cloud & DevOps</h1>
    </div>
    <div class="content__services">
      <p>We use our expertise in cloud and server solutions to derive and build high-performing environments that helps you cut down cloud spending, automate infrastructure monitoring, and increase architectural flexibility.</p>
    </div>
  </div>
</div>
</div>
</template>

<script>
export default {
  name: "Services"
}
</script>

<style scoped>
.services{
  margin-bottom: 124px;
}
.services__content{
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
</style>
