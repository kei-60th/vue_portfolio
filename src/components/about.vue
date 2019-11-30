<template>
  <div class = "background">
    <div class = "content">
      <h1 class= "pagetitle">Profile</h1>
      <div class = "cardwrapper">
        <div class = "profilecard">
          <v-card
            class="mx-auto"
            max-width="400"
          >
          <div class = "imagewrapper">
            <v-img
              class="white--text align-end profile-img"
              height="300px"
              src="../assets/kei.jpg"
            >
            </v-img>
            </div>
            <v-card-title>中田 慧</v-card-title>
            <v-card-subtitle class="pb-0">1994年生まれ 名城大学卒業</v-card-subtitle>

            <v-card-text class="text--primary">
              <div>愛知県出身です。<br>大学卒業後,Sier系のIT企業に勤めておりました。<br>その後8月に退職して同月にプログラミングスクールに通い、11月に卒業しました。<br>卒業後もプログラミングの学習は継続して行なっております。</div>
            </v-card-text>
            <v-card-title class = "study">主な学習分野</v-card-title>
            <v-card-subtitle class="pb-0">Haml, SCSS,Ruby,Ruby on Rails, JavaScript, jQuery, GitHub, AWS, Vue.js</v-card-subtitle>
            <v-card-text class="text--primary">
            </v-card-text>
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

.profilecard{
  margin-bottom: 100px;
}

.imagewrapper{
  background-color:gray;
}

.profile-img{
  margin:0px 40px 0;
}

.study{
  padding-top:0;
}

</style>