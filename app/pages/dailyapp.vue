<template>
  <v-layout
    fill-height
    justify-center
    align-center>
    <v-flex xs12 lg6>
      <div class="text-xs-center">
        <span class="headline">100日で一歩上の開発者へ</span>
      </div>
      <div class="mail-panel">
        <v-text-field
          label="メールアドレスを入力"
I         append-outer-icon="mail"
          outline
          @click:append-outer="sendMail()"
        >
        </v-text-field>
      </div>
    </v-flex>
  </v-layout>
</template>

<script>
export default {
  data () {

  },
  methods: {
    sendMail () {
      console.log("sent email")
    }
  }
}
</script>

<style>
.v-icon {
  font-size: 35px;
}
</style>
