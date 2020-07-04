<template>
  
    <v-app>
      <v-app-bar app dark>
        サイト名
      </v-app-bar>
          <br><br><br>
          <Rakuten></Rakuten>
    </v-app> 
  
</template>

<script>
import Rakuten from './components/Rakuten.vue'
export default {
  components: {
    Rakuten
  }
}

</script>