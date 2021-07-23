<template>
  <div id="app">
    <head> </head>
    <Header></Header>
    <div class="Introduction">
      <p>
        ある日の帰り道に、「虹」を見ました。<br />なんだか嬉しくて、いいことがあるような気持ちになりました。<br />「虹」のように、心惹かれる瞬間を提供し、誰かと誰かを繋ぐ。<br />こんな想いを軸に、お仕事をしていきます。<br />ポートフォリオをご覧になって頂いている皆様との出会いに感謝しています。<br />お時間を頂き、ありがとうございます。<br>宜しくお願い致します。
      </p>
    </div>
    <div id="profile">
      <h2>～ プロフィール ～</h2>
      <div class="profile-wrap-1">
        <div class="left">
          <p class="left-1">Onogawa Chisa</p>
          <p class="left-2">斧川 千紗</p>
        </div>
        <div class="right">
          <p class="right-1">1993年　大阪生まれ</p>
          <p class="right-2">2018年　人間総合科学大学 卒業</p>
          <p class="right-4">2021年　COACHTECH 卒業</p>
          <p class="right-3">
            2018年より、二酸化塩素を使用した除菌消臭剤を製造する会社に勤務
          </p>
        </div>
      </div>
      <div class="profile-wrap-2">
        <div class="hobby">
          <p class="hobby-1">最近の癒し：猫</p>
          <p class="hobby-2">好きな食べ物：チョコレート</p>
          <p class="hobby-3">最近の始めたこと：ジムで筋トレを始めました</p>
        </div>
      </div>
    </div>
    <div id="programmingLanguage">
      <h2>～ 習得言語 ～</h2>
      <div class="img-wrap">
        <img class="img-1 img" src="../src/assets/html-5.svg" alt="" />
        <img class="img-2 img" src="../src/assets/css-3.svg" alt="" />
        <div class="laravel">
          <p>Laravel</p>
          <img class="img-3 img" src="../src/assets/laravel.svg" alt="" />
        </div>
        <div class="vuejs">
          <p>Vue.js</p>
          <img class="img-4 img" src="../src/assets/vue.svg" alt="" />
        </div>
        <div class="mysql">
          <p>MySQL</p>
          <img class="img-5 img" src="../src/assets/mysql.svg" alt="" />
        </div>
        <img class="img-6 img" src="../src/assets/heroku.svg" alt="" />
        <div class="github">
          <p>GitHub</p>
          <img class="img-7 img" src="../src/assets/github-icon.svg" alt="" />
        </div>
        <img class="img-8 img" src="../src/assets/wordpress.svg" alt="" />
      </div>
    </div>
    <div id="products">
      <h2>～ 作品紹介 ～</h2>
      <div class="product-link">
        <p><a href="https://flamboyant-spence-4598cd.netlify.app/" target="_blank">タイピングゲーム</a></p>
        <a href="https://github.com/chisa232/TypingGame.git" target="_blank">
          <button class="github-link">
            <img
              class="github-1"
              src="../src/assets/github-icon.svg"
              alt=""
            /><img class="github-2" src="../src/assets/github.svg" alt="" />
          </button>
        </a>
      </div>
    </div>
    <div id="contact">
      <h2>～ お問い合わせ ～</h2>
      <div class="contact-wrap">
        <div class="contact-left">
          <a href="mailto:okanmax@yahoo.co.jp">
          <img class="contact-img-1" src="../src/assets/mail.png" alt="" />
          <img class="contact-img-2" src="../src/assets/click.png" alt="" />
          </a>
        </div>
        <div class="contact-right">
          <p>
            お問い合わせは、メールにてお願い致します。<br />
            1～3日以内に、返信させて頂きます。<br />宜しくお願い致します。
          </p>
        </div>
      </div>
    </div>
    <Footer></Footer>
  </div>
</template>


<script>
import Header from "../src/components/Header.vue";
import Footer from "../src/components/Footer.vue";

export default {
  components: {
    Header,
    Footer
  },
};
</script>

<style >
/* リセットcss */
html,
body,
div,
span,
object,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
blockquote,
pre,
abbr,
address,
cite,
code,
del,
dfn,
em,
img,
ins,
kbd,
q,
samp,
small,
strong,
sub,
sup,
var,
b,
i,
dl,
dt,
dd,
ol,
ul,
li,
fieldset,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td,
article,
aside,
canvas,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section,
summary,
time,
mark,
audio,
video {
  margin: 0;
  padding: 0;
  border: 0;
  outline: 0;
  font-size: 100%;
  vertical-align: baseline;
  background: transparent;
}

body {
  line-height: 1;
}

article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section {
  display: block;
}

nav ul {
  list-style: none;
}

blockquote,
q {
  quotes: none;
}

blockquote:before,
blockquote:after,
q:before,
q:after {
  content: "";
  content: none;
}

a {
  margin: 0;
  padding: 0;
  font-size: 100%;
  vertical-align: baseline;
  background: transparent;
}

/* change colours to suit your needs */
ins {
  background-color: #ff9;
  color: #000;
  text-decoration: none;
}

/* change colours to suit your needs */
mark {
  background-color: #ff9;
  color: #000;
  font-style: italic;
  font-weight: bold;
}

del {
  text-decoration: line-through;
}

abbr[title],
dfn[title] {
  border-bottom: 1px dotted;
  cursor: help;
}

table {
  border-collapse: collapse;
  border-spacing: 0;
}

/* change border colour to suit your needs */
hr {
  display: block;
  height: 1px;
  border: 0;
  border-top: 1px solid #cccccc;
  margin: 1em 0;
  padding: 0;
}

input,
select {
  vertical-align: middle;
}






.Introduction {
  width: 100vw;
  font-family: "メイリオ", "Meiryo", sans-serif;
  font-weight: bold;
  font-size: 2vw;
  letter-spacing: 3px;
  line-height: 4vw;
  margin: 10% auto;
  text-align: center;
}
#profile {
  font-family: "メイリオ", "Meiryo", sans-serif;
  font-weight: bold;
}
#profile h2 {
  width: 26vw;
  font-size: 3vw;
  color: #ff7b00;
  margin: 10vw auto 3vw;
}
.profile-wrap-1 {
  width:100%;
  margin: 5% auto;
  display: flex;
}
.left {
  height: 80px;
  width:50%;
  margin: 5vw auto 0;
}
.left-1 {
  font-size: 2vw;
  letter-spacing: 5px;
  text-align: center;
  margin-bottom: 3%;
}
.left-2 {
  font-size: 4vw;
  letter-spacing: 10px;
  text-align: center;
}
.right {
  width: 70%;
  margin: 2vw auto;
  font-size: 2vw;
  letter-spacing: 3px;
  line-height: 4vw;
}
.right-3 {
  width: 100%;
  margin-top: 3%;
  text-align:center ;
}
.profile-wrap-2 {
  width: 100%;
  margin: 5vw auto;
}
.hobby {
  width: 100%;
  margin: 0 auto;
  font-size: 2vw;
  line-height: 4vw;
  text-align: center;
}
.hobby-3 {
  width: 100%;
}
#programmingLanguage {
  font-family: "メイリオ", "Meiryo", sans-serif;
  font-weight: bold;

}
#programmingLanguage h2 {
  width: 20vw;
  font-size: 3vw;
  color: #ff7b00;
  margin: 10vw auto 5vw;
}
.img-1,
.img-2,
.img-6,
.img-8 {
  width: 13vw;
  align-items: center;
  margin: 2vw;
}
.img-wrap {
  display: flex;
  margin: 5vw auto;
  width: 70vw;
  flex-wrap: wrap;
  justify-content: center;
}
.laravel,
.vuejs,
.mysql,
.github {
  width: 13vw;
  margin: 2vw 2vw;
}
.img-3,
.img-4,
.img-5,
.img-7 {
  width: 13vw;
  margin: 1vw auto 0;
}
.laravel p,
.vuejs p,
.mysql p,
.github p {
  font-size: 1.8rem;
  text-align: center;
  font-family: "Franklin Gothic Medium", "メイリオ", sans-serif;
}
#products h2 {
  width: 20vw;
  font-size: 3vw;
  color: #ff7b00;
  margin: 7vw auto 5vw;
}
.product-link {
  display: flex;
  width: 100vw;
  margin: auto;
  justify-content: center;
}
.product-link p {
  font-family: "Franklin Gothic Medium", "メイリオ", "Meiryo";
  font-weight: bold;
  font-size: 2.5vw;
  letter-spacing: 3px;
  padding: 1.5vw 1vw;
  list-style: none;
}
#products a {
  text-decoration: none;
  color: black;
}
a:hover {
  color: rgb(66, 65, 65);
  opacity: 0.5;
}
.github-link {
  display: flex;
  background-color: white;
  padding: 5px 20px;
  border: solid 1px;
  border-radius: 40px;
  margin: 1vw 3vw;
}
.github-1 {
  width: 3vw;
  margin-right: 5px;
}
.github-2 {
  width: 8vw;
  margin-top: 0.5vw;
}
.contact-wrap{
  display: flex;
  width: 95%;
  margin: 0 auto;
  justify-content: center;
}
#contact h2 {
  width: 26vw;
  font-size: 3vw;
  color: #ff7b00;
  margin: 10vw auto 5vw;
}
.contact-img-1 {
  width: 15vw;
}
.contact-img-2 {
  width: 7vw;
}
.contact-right{
  font-family: "メイリオ", "Meiryo", sans-serif;
  font-weight: bold;
  font-size: 2vw;
  letter-spacing: 2px;
  line-height: 3vw;
  text-align: center;
  margin: auto 0;
}




@media screen and ( max-width:768px){ 
  /*　画面サイズが768pxまではここを読み込む　*/
.Introduction {
  width: 100vw;
  font-family: "メイリオ", "Meiryo", sans-serif;
  font-weight: bold;
  font-size: 2vw;
  letter-spacing: 1px;
  line-height:5vw;
  margin: 10vw auto;
  text-align: center;
}
#profile {
  font-family: "メイリオ", "Meiryo", sans-serif;
  font-weight: bold;
}
#profile h2 {
  width: 35vw;
  font-size: 4vw;
  color: #ff7b00;
  margin: 15vw auto 3vw;
}
.profile-wrap-1 {
  width: 85%;
  flex-wrap: wrap;
  margin: 2% auto;
}
.left {
  height: 50px;
  width: 100%;
  margin: 4vw auto 0;
}
.left-1 {
  font-size:2vw;
  letter-spacing: 3px;
  text-align: center;
  margin-bottom: 2%;
}
.left-2 {
  font-size: 6vw;
  letter-spacing: 3px;
  text-align: center;
}
.right {
  width: 100%;
  margin: 8vw auto;
  font-size: 2vw;
  letter-spacing: 2px;
  line-height: 4vw;
  text-align:center ;
}
.right-3 {
  width: 100%;
  text-align:center ;
}
.profile-wrap-2 {
  width: 100%;
  margin: 0 auto;
}
.hobby {
  width: 100%;
  margin: 0 auto ;
  font-size: 2vw;
  line-height: 4vw;
  text-align: center;
}
.hobby-3 {
  width: 100%;
}
#programmingLanguage {
  font-family: "メイリオ", "Meiryo", sans-serif;
  font-weight: bold;
}
#programmingLanguage h2 {
  width: 27vw;
  font-size: 4vw;
  color: #ff7b00;
  margin: 15vw auto 5vw;
}
.img-1,
.img-2,
.img-6,
.img-8 {
  width:10vw;
  align-items: center;
  margin: 2vw 2vw;
}
.img-wrap {
  display: flex;
  margin: 0 auto;
  width: 60vw;
  flex-wrap: wrap;
  justify-content: space-between;
}
.laravel,
.vuejs,
.mysql,
.github {
  width: 10vw;
  margin: 2vw 2vw;
}
.img-3,
.img-4,
.img-5,
.img-7 {
  width: 10vw;
  margin: 1vw auto 0;
}
.laravel p,
.vuejs p,
.mysql p,
.github p {
  font-size: 3vw;
  text-align: center;
  font-family: "Franklin Gothic Medium", "メイリオ", sans-serif;
}
#products h2 {
  width:27vw;
  font-size: 4vw;
  color: #ff7b00;
  margin: 10vw auto 5vw;
}
.product-link {
  display: flex;
  width: 100vw;
  margin: auto;
  justify-content: center;
}
.product-link p {
  font-family: "Franklin Gothic Medium", "メイリオ", "Meiryo";
  font-weight: bold;
  font-size: 2vw;
  letter-spacing: 1px;
  padding: 2vw 0 ;
  list-style: none;
}
#products a {
  text-decoration: none;
  color: black;
}
a:hover {
  color: rgb(66, 65, 65);
  opacity: 0.5;
}
.github-link {
  background-color: white;
  padding: 2px 10px;
  border: solid 1px;
  border-radius: 40px;
}
.github-1 {
  width: 3vw;
  margin-right: 3px;
}
.github-2 {
  width: 7vw;
}
.contact-wrap{
  width: 100%;
  margin: 0 auto 10vw;
  align-items: center;
  justify-content: center;
}
#contact h2 {
  width: 35vw;
  font-size: 4vw;
  color: #ff7b00;
  margin: 10vw auto 5vw;
}
.contact-img-1 {
  width: 15vw;
}
.contact-img-2 {
  width: 9vw;
}
.contact-right{
  text-align: center;
  font-family: "メイリオ", "Meiryo", sans-serif;
  font-weight: bold;
  font-size: 2vw;
  letter-spacing: 0px;
  line-height: 4vw;
}
}





@media screen and (min-width:769px) and ( max-width:1024px) {
    /*　画面サイズが769pxから1024pxまではここを読み込む　*/
.Introduction {
  width: 100vw;
  font-family: "メイリオ", "Meiryo", sans-serif;
  font-weight: bold;
  font-size: 2vw;
  letter-spacing: 1px;
  line-height: 4vw;
  margin: 10vw auto 1vw;
  text-align: center;
}
#profile {
  font-family: "メイリオ", "Meiryo", sans-serif;
  font-weight: bold;
}
#profile h2 {
  width: 35vw;
  font-size: 4vw;
  color: #ff7b00;
  margin: 10vw auto 3vw;
}
.profile-wrap-1 {
  width: 85%;
  flex-wrap: wrap;
  margin: 2% auto;
}
.left {
  height: 80px;
  width: 100%;
  margin: 4vw auto 0;
}
.left-1 {
  font-size: 1vw;
  letter-spacing: 0.5vw;
  text-align: center;
  margin-bottom: 2%;
}
.left-2 {
  font-size: 4vw;
  letter-spacing: 10px;
  text-align: center;
}
.right {
  width: 100%;
  margin: 2vw auto;
  font-size: 2vw;
  letter-spacing: 3px;
  line-height: 4vw;
  text-align:center ;
}
.right-3 {
  width: 100%;
  text-align:center ;
}
.profile-wrap-2 {
  width: 100%;
  margin: 0 auto;
}
.hobby {
  width: 100%;
  margin: 0 auto;
  font-size: 2vw;
  line-height: 4vw;
  text-align: center;
}
.hobby-3 {
  width: 100%;
}
#programmingLanguage {
  font-family: "メイリオ", "Meiryo", sans-serif;
  font-weight: bold;
}
#programmingLanguage h2 {
  width: 27vw;
  font-size: 4vw;
  color: #ff7b00;
  margin: 15vw auto 5vw;
}
.img-1,
.img-2,
.img-6,
.img-8 {
  width:12vw;
  align-items: center;
  margin: 3vw 2vw;
}
.img-wrap {
  display: flex;
  margin: 0 auto;
  width: 70vw;
  flex-wrap: wrap;
  justify-content: space-between;
}
.laravel,
.vuejs,
.mysql,
.github {
  width: 12vw;
  margin: 3vw 2vw;
}
.img-3,
.img-4,
.img-5,
.img-7 {
  width: 12vw;
  margin: 1.5vw auto 0;
}
.laravel p,
.vuejs p,
.mysql p,
.github p {
  font-size: 3vw;
  text-align: center;
  font-family: "Franklin Gothic Medium", "メイリオ", sans-serif;
}
#products h2 {
  width:27vw;
  font-size: 4vw;
  color: #ff7b00;
  margin: 10vw auto 5vw;
}
.product-link {
  display: flex;
  width: 70vw;
  margin: auto;
  justify-content: center;
}
.product-link p {
  font-family: "Franklin Gothic Medium", "メイリオ", "Meiryo";
  font-weight: bold;
  font-size: 3vw;
  letter-spacing: 1px;
  padding: 2vw 0 ;
  list-style: none;
}
#products a {
  text-decoration: none;
  color: black;
}
a:hover {
  color: rgb(66, 65, 65);
  opacity: 0.5;
}
.github-link {
  background-color: white;
  padding: 6px 10px;
  border: solid 1px;
  border-radius: 40px;
}
.github-1 {
  width: 3vw;
  margin-right: 3px;
}
.github-2 {
  width: 7vw;
}
.contact-wrap{
  display: flex;
  width: 77%;
  margin: 0 auto;
  align-items: center;
  justify-content: center;
}
#contact h2 {
  width: 35vw;
  font-size: 4vw;
  color: #ff7b00;
  margin: 15vw auto 5vw;
}
.contact-img-1 {
  width: 13vw;
}
.contact-img-2 {
  width: 8vw;
}
.contact-right{
  font-family: "メイリオ", "Meiryo", sans-serif;
  font-weight: bold;
  font-size: 2vw;
  letter-spacing: 1px;
  line-height: 3vw;
  text-align: center;
}
}
</style>