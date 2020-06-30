<template>
  <div>
    <v-app>
      <v-app-bar app>
        実機ちゃん
      </v-app-bar>

      <!-- Sizes your content based upon application components -->
      <v-main>

        <!-- Provides the application the proper gutter -->
        <v-container fluid>
          
          <!-- If using vue-router -->
          <br><br><br><br>
          <Rakuten></Rakuten>
        </v-container>
      </v-main>

      <v-footer app>
        実機ちゃん
      </v-footer>
    </v-app> 
  </div>
</template>

<script>
import Rakuten from './components/Rakuten.vue'
export default {
  components: {
    Rakuten
  }
}

</script>
