<template>
    <h1>Bienvenido a mi primera aplicacion</h1>
</template>

<script>
export default {
  head(){
    return {
      title:'Aplicacion Nuxt Post | Home',
      meta:[
        {
          hid:'description',
          name:'description',
          content:'Website about posts'
        }
      ],
      htmlAttrs:{
        lang:'es'
      }
    }
  }
}
</script>