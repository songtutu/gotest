<template>
  <v-card class="mx-auto" max-width="300">
    <v-img src="../assets/bluebg.png">
      <v-card-title>
        <v-col align="center">
          <v-avatar size="130" color="grey">
            <img src="../assets/123.jpg" alt="John" />
          </v-avatar>
          <div class="ma-4 white--text">weject</div>
        </v-col>
      </v-card-title>

      <v-divider color="white"></v-divider>
    </v-img>
    <v-col>
      <div class="ma-3">About Me:</div>
      <div class="ma-3">111</div>
    </v-col>
    <v-divider color="indigo"></v-divider>
    <v-list nav dense>
      <v-list-item>
        <v-list-item-icon class="ma-3">
          <v-icon>{{'mdi-qqchat'}}</v-icon>
        </v-list-item-icon>
        <v-list-item-content class="grey--text">12334566</v-list-item-content>
      </v-list-item>

      <v-list-item>
        <v-list-item-icon class="ma-3">
          <v-icon>{{'mdi-wechat'}}</v-icon>
        </v-list-item-icon>
        <v-list-item-content class="grey--text">12334566</v-list-item-content>
      </v-list-item>

      <v-list-item>
        <v-list-item-icon class="ma-3">
          <v-icon>{{'mdi-sina-weibo'}}</v-icon>
        </v-list-item-icon>
        <v-list-item-content class="grey--text">12334566</v-list-item-content>
      </v-list-item>

      <v-list-item>
        <v-list-item-icon class="ma-3">
          <v-icon>{{'mdi-facebook'}}</v-icon>
        </v-list-item-icon>
        <v-list-item-content class="grey--text">12334566</v-list-item-content>
      </v-list-item>

      <v-list-item>
        <v-list-item-icon class="ma-3">
          <v-icon>{{'mdi-twitter'}}</v-icon>
        </v-list-item-icon>
        <v-list-item-content class="grey--text">12334566</v-list-item-content>
      </v-list-item>

      <v-list-item>
        <v-list-item-icon class="ma-3">
          <v-icon>{{'mdi-email'}}</v-icon>
        </v-list-item-icon>
        <v-list-item-content class="grey--text">12334566</v-list-item-content>
      </v-list-item>
    </v-list>
  </v-card>
</template>
<script>
export default {
  data() {
    return {}
  }
}
</script>
<style lang="">
</style>