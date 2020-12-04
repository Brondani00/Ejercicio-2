
<template>
  <div>
      
  </div>
  
</template>

<script>
Vue.component('Boton', {
    props: {value:String ,spanX:Number, spanY:Number}, 
    data: function () 
    { 
    return {value}
    },
    template: '<Button  id="boton-id"  v-on:click="this.value">=</Button>',
    
})
    value = document.getElementById("boton-id").value ;
export default {
    name: 'Boton',
  components: { Boton }
}
</script>



