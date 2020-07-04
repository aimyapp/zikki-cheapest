<template>
  <v-container class="grey lighten-4" fluid>
    <v-card-title>{{ shopName }}</v-card-title>
    <v-row>
      <v-col v-for="zikki in zikkis" :key="zikki" cols="12" sm="6" md="4">
        <v-card>
          <v-img
            :src="`https://upload.wikimedia.org/wikipedia/commons/0/0e/No_image.jpg`"
            height="300px"
            width="200px"
          ></v-img>
          <v-card-subtitle class="pb-0">機種名: {{ zikki }}</v-card-subtitle>
          <v-card-text class="text--primary">
            <div style="color:red">00,000円 (送料別)</div>

            <div>説明文</div>
          </v-card-text>
          <v-card-actions>
            <v-btn color="orange" text>購入ページへ</v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  data: () => ({
    shopName: "楽天市場",
    zikkis: [
      "HANABI",
      "VERSUS",
      "サンダーVリボルト",
      "B-MAX",
      "クランキーコレクション",
      "ゲッターマウス",
      "アレックス",
      "ドンちゃん2",
      "サンダーVライトニング"
    ]
  })
};
</script> 

<style scoped>
</style>