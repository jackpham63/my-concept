<template>
<div class="wrap">
  <div class="page">
    <slot name="header" >
      <Header/>
    </slot>
    <slot name="content">
      <div>content</div>
    </slot>
    <slot name="footer">
      <Footer/>
    </slot>
<!--    <slot name="content">
      <div>content</div>
    </slot>
    <slot name="footer">
      <div>footer</div>
    </slot>-->
  </div>
</div>
</template>

<script>
import Header from "~/components/common/Header";
import Footer from "~/components/common/Footer";

export default {
  name: "CommonTemplate",
  components: {Footer, Header}
}
</script>

<style scoped>
.wrap{
  width: 100%;
  background-color: #1E1E1E;;
  box-sizing: border-box;
  margin: 0;
  padding: 0;

}
.page {
  max-width: 1440px;
  margin: auto;
  background-color: transparent;
  padding: 0 135px;
}
</style>
