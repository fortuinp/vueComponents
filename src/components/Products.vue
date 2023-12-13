<template>
    <div>
      <h2>Child component</h2>
     <p>{{ greeting }}</p>
    </div>
</template>

<script>
    export default {
        name: 'ProductComp',
        //or rename the file for multiple word
        props:['greeting']
    }
</script>

<style scoped>

</style>