<template>
<div>Child Component</div>
</template>
<script>
export default {
  name: 'ChildComp',
  beforeCreate() {
    console.log('ChildComp beforeCreate()')
  },
  created() {
    console.log('ChildComp created()')
  },
  beforeMount() {
    console.log('ChildComp beforeMount()')
  },
  mounted() {
    console.log('ChildComp mounted()')
  },
  beforeUpdate() {
    console.log('ChildComp beforeUpdate()')
  },
  updated() {
    console.log('ChildComp updated()')
  },
  beforeUnmount() {
    console.log('ChildComp beforeUnmount()')
  },
  unmounted() {
    console.log('ChildComp unmounted()')
  },
}
</script>
<style scoped>

</style>