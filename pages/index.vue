<template>
  <common-template >
  <div slot="content">
    <Banner/>
    <who-are-we/>
    <services/>
    <make-us/>
   <solution/>
    <we-did/>
  </div>
  </common-template>
</template>

<script>
import CommonTemplate from "~/components/common/CommonTemplate";
import Banner from "~/components/HomePage/Banner";
import WhoAreWe from "~/components/HomePage/WhoAreWe";
import Services from "@/components/HomePage/Services";
import MakeUs from "@/components/HomePage/MakeUs";
import Solution from "@/components/HomePage/Solution";
import WeDid from "~/components/HomePage/WeDid";
export default {
  name: 'IndexPage',
  components: {WeDid, Solution, MakeUs, Services, WhoAreWe, Banner, CommonTemplate }
}
</script>
