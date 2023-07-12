<template>
  <DataComp/>
  <DemoOne/>
  <DemoTwo/>
  <MethodS/>
  <VModel/>
  <ComputedComp/>
  <WatchComp/>
  <ProvideInject/>
  <ChildA/>
  <ChildB/>
  <ChildC/>
  <TemplateRef/>
  <PersonComp/>
  <PersonGreeting/>
</template>

<script>
import DataComp from "@/components/DataComp.vue";
import DemoOne from "@/components/DemoOne.vue";
import DemoTwo from "@/assets/DemoTwo.vue";
import MethodS from "@/components/MethodS.vue";
import VModel from "@/components/VModel.vue";
import ComputedComp from "@/components/ComputedComp.vue";
import WatchComp from "@/components/WatchComp.vue";
import ProvideInject from "@/components/ProvideInject.vue";
import ChildA from "@/components/ChildA.vue";
import ChildB from "@/components/ChildB.vue";
import ChildC from "@/components/ChildC.vue";
import TemplateRef from "@/components/TemplateRef.vue";
import PersonComp from "@/components/PersonComp.vue";
import PersonGreeting from "@/components/PersonGreeting.vue";


export default {
  name: 'App',
  components: {

    PersonGreeting,
    PersonComp,
    TemplateRef,
    ChildC,
    ChildB,
    ChildA,
    ProvideInject,
    WatchComp,
    ComputedComp,
    VModel,
    MethodS,
    DataComp,
    DemoOne,
    DemoTwo,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
