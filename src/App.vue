<template>
  <div>
    <h1>{{titulo}}</h1>
    <ul>
      <li v-for="foto of fotos">
        <img :src="foto.url" :alt="foto.titulo"/>
      </li>
    </ul>
    
  </div>
</template>

<script>
export default {
  data(){
    return {
      titulo: "AluraPic",
      fotos: 
      [
        {
          url: "https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcTwV4kVzT5McBdGSgqlVeRzubrNH_mOrrkKseDOGFURq20HmsrelEfMU7It",
          titulo: "Cachorro 1"
        },
        {
          url: "https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcTwV4kVzT5McBdGSgqlVeRzubrNH_mOrrkKseDOGFURq20HmsrelEfMU7It",
          titulo: "Cachorro 2"
        }
      ]
    }
  }
}
</script>

<style lang="scss">

</style>
