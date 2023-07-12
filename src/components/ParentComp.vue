<template>
<div>
  Parent Component
  <button @click="showChild= !showChild">Toggle Child</button>
  <ChildComp v-if="showChild"/>
</div>

</template>
<script>
import ChildComp from "@/components/ChildComp.vue";
export default {
  components:{ChildComp},
  name:'ParentComp',
  data(){
    return{
      showChild:true,
    }
  },
  beforeCreate() {
    console.log('ParentComp beforeCreate()')
  },
  created() {
    console.log('ParentComp created()')
  },
  beforeMount() {
    console.log('ParentComp beforeMount()')
  },
  mounted() {
    console.log('ParentComp mounted()')
  },
  beforeUpdate() {
    console.log('ParentComp beforeUpdate()')
  },
  updated() {
    console.log('ParentComp updated()')
  },
  beforeUnmount() {
    console.log('ParentComp beforeUnmount()')
  },
  unmounted() {
    console.log('ParentComp unmounted()')
  },
}
</script>
<style scoped>

</style>