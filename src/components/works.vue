<template>
  <div class = "background">
    <div class = "content">
      <h1 class= "pagetitle">My works</h1>
      <div class = "cardwrapper">
        <div class = "cardbox">
          <v-card
            class="mx-auto"
            max-width="400"
          >
            <v-img
              class="white--text align-end"
              height="200px"
              src="../assets/portfoliosite.png"
            >
            </v-img>
            <v-card-title>Portfolio</v-card-title>
            <v-card-subtitle class="pb-0">Vue.js, Vuetify</v-card-subtitle>

            <v-card-text class="text--primary">
              <div>自分のポートフォリオサイトです<br>プロフィールや作品を公開しています</div>
            </v-card-text>

            <!-- <v-card-actions>
              <v-btn
                color="orange"
                text
              >
                Share
              </v-btn>

              <v-btn
                color="orange"
                text
              >
                Explore
              </v-btn>
            </v-card-actions> -->
          </v-card>

          <v-card
            class="mx-auto"
            max-width="400"
          >
            <v-img
              class="white--text align-end"
              height="200px"
              src="../assets/pompompro.png"
            >
            </v-img>

            <v-card-title>Pompompro</v-card-title>
            <v-card-subtitle class="pb-0">Ruby, Rails, jQuery, MySQL, AWS</v-card-subtitle>

            <v-card-text class="text--primary">
              <div>ToDo管理とタイマー計測のついた自己管理アプリです<br>成果をTwitterに投稿することもできます</div>
            </v-card-text>

            <!-- <v-card-actions>
              <v-btn
                color="orange"
                text
              >
                Share
              </v-btn>

              <v-btn
                color="orange"
                text
              >
                Explore
              </v-btn>
            </v-card-actions> -->
          </v-card>

          <v-card
            class="mx-auto"
            max-width="400"
          >
            <v-img
              class="white--text align-end"
              height="200px"
              src="../assets/chat-space.png"
            >
            </v-img>
            <v-card-title>chat-space</v-card-title>
            <v-card-subtitle class="pb-0">Ruby, Rails, jQuery, MySQL, AWS</v-card-subtitle>

            <v-card-text class="text--primary">
              <div>名前の通りチャットアプリです。<br>ユーザー間でチャットグループの作成やメッセージの送信ができます。</div>
            </v-card-text>

            <!-- <v-card-actions>
              <v-btn
                color="orange"
                text
              >
                Share
              </v-btn>

              <v-btn
                color="orange"
                text
              >
                Explore
              </v-btn>
            </v-card-actions> -->
          </v-card>

          <v-card
            class="mx-auto"
            max-width="400"
          >
            <v-img
              class="white--text align-end"
              height="200px"
              src="../assets/no_image.png"
            >
            </v-img>
            <v-card-title>freemarket_sample_60d</v-card-title>
            <v-card-subtitle class="pb-0">Ruby, Rails, jQuery, MySQL, AWS</v-card-subtitle>

            <v-card-text class="text--primary">
              <div>スクールのチーム開発の成果物で、<br>フリマアプリのクローンサイトとなります。<br>自分はユーザー登録機能,購入機能を担当しました</div>
            </v-card-text>

            <!-- <v-card-actions>
              <v-btn
                color="orange"
                text
              >
                Share
              </v-btn>

              <v-btn
                color="orange"
                text
              >
                Explore
              </v-btn>
            </v-card-actions> -->
          </v-card>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
</script>

<style>

.background{
  background-color:whitesmoke;
}

.content{
  margin-top: 65px;
}

.pagetitle{
  color:#1976d2;
  font-size:40px;
  font-family: 'ヒラギノ丸ゴ ProN','Hiragino Maru Gothic ProN';
  margin-left:20px;
  border-bottom:double;
  margin-bottom:10px;
}

.cardwrapper{
  display:flex;
  justify-content:center;
}

.cardbox{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-evenly;
  width:80%;
}

.v-card{
  margin-bottom:30px;
}

.v-card__title{
  color:black;
  opacity:0.87
}

</style>