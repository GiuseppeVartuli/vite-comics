<script>
import DcHeader from "./components/DcHeader.vue";
import DcMain from "./components/DcMain.vue";
import DcFooter from "./components/DcFooter.vue";
import ComicsCard from "./components/ComicsCard.vue";

export default {
  name: "App",
  components: {
    DcHeader,
    DcMain,
    DcFooter,
    ComicsCard,
  },
};
</script>

<template>
  <DcHeader></DcHeader>
  <DcMain></DcMain>
  <DcFooter></DcFooter>
</template>

<style></style>
