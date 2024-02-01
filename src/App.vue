<script>
import DcHeader from "./components/DcHeader.vue";
import DcMain from "./components/DcMain.vue";
import DcFooter from "./components/DcFooter.vue";

export default {
  name: "App",
  components: {
    DcHeader,
    DcMain,
    DcFooter,
  },
};
</script>

<template>
  <DcHeader></DcHeader>
  <DcMain></DcMain>
  <DcFooter></DcFooter>
</template>

<style></style>
