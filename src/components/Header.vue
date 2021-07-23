<template>
  <header>
        <div class="hello">
          <p>はじめまして<br>よろしくお願いします</p>
        </div>
      <div class="header-wrap">
        <div class="header-logo">
          <h2>Onogawa Chisa</h2>
          <h1>斧川 千紗</h1>
        </div>
        <div class="header-nav">
          <ul>
            <li><a href="#profile">プロフィール</a></li>
            <li><a href="#programmingLanguage">習得言語</a></li>
            <li><a href="#products">作品紹介</a></li>
            <li><a href="#contact">お問い合わせ</a></li>
          </ul>
        </div>
      </div>
  </header>
</template>

<script>
</script>


<style scoped>
header{
  font-size: 62.5%;
}
.hello {
  background-image:url(../assets/eyecatch.jpg);
  background-size:cover ;
  background-position: center;
  width: 100vw;
  height: 45vw;
}
.hello p{
  width: 70vw;
  color: rgba(255, 255, 255, 0.705);
  font-family: "メイリオ", "Meiryo", sans-serif;
  font-size: 5vw;
  line-height: 7vw;
  text-align: center;
  letter-spacing: 5px;
  position: relative;
  top: 55%;
  left: 50%;
  transform: translate(-50%,-50%);
  opacity: 0;
  -webkit-animation: example 1s ease 1s 1 forwards;
  animation: example 1s ease 1s 1 forwards;
}
@-webkit-keyframes example {
  100% {
    opacity: 1;
  }
}
@keyframes example {
  100% {
    opacity: 1;
  }
}
.header-wrap {
  font-family: "メイリオ", "Meiryo", sans-serif;
  display: flex;
  font-weight: bold;
  width: 95%;
  margin: 2% auto;
  justify-content: center;
}
.header-logo {
  color: #ffb800;
  height: 50px;
  width: 25%;
  margin: 6vw 0 0 0 ;
}
.header-logo h2 {
  font-size: 2vw;
  letter-spacing: 2px;
  text-align:center;
  margin-bottom: 3%;
}
.header-logo h1 {
  font-size: 3vw;
  letter-spacing: 10px;
  text-align: center;
  margin: 0;
}
.header-nav {
  width: 75%;
  margin:7vw 0 auto;
}
.header-nav ul {
  display: flex;
  height: 50px;
  align-items: center;
  justify-content: space-between;
  margin:0 5% ;
}
.header-nav li {
  list-style: none;
  margin-left: 2%;
  font-size: 2.5vw;
  color: #ffb800;
}
.header-nav a {
  text-decoration: none;
  color: #ffb800;
}
a:hover {
  color: #fd9001;
  opacity: 0.5;
}





@media screen and ( max-width:768px){ 
/*　画面サイズが768pxまではここを読み込む　*/

  .hello p{
  width: 100vw;
  color: rgba(255, 255, 255, 0.705);
  font-family: "メイリオ", "Meiryo", sans-serif;
  font-size: 6vw;
  line-height: 7vw;
  text-align: center;
  letter-spacing: 5px;
  position: relative;
  top: 60%;
  left: 50%;
  transform: translate(-50%,-50%);
  opacity: 0;
  -webkit-animation: example 1s ease 1s 1 forwards;
  animation: example 1s ease 1s 1 forwards;
}
@-webkit-keyframes example {
  100% {
    opacity: 1;
  }
}
@keyframes example {
  100% {
    opacity: 1;
  }
}
.header-wrap {
  font-family: "メイリオ", "Meiryo", sans-serif;
  font-weight: bold;
  width: 100%;
  margin: 2% auto;
  justify-content: center;
  flex-wrap: wrap;
}
.header-logo {
  color: #ffb800;
  height: 100%;
  width: 100%;
  margin: 5vw 0 0 3vw ;
}
.header-logo h2 {
  font-size: 1vw;
  letter-spacing: 0.5vw;
  text-align: center;
  margin-bottom: 1%;
}
.header-logo h1 {
  font-size: 5vw;
  letter-spacing: 5px;
  text-align: center;
  margin: 0;
}
.header-nav {
  width: 100%;
  padding: 1%;
  margin:0 auto;
}
.header-nav ul {  
  display: flex;
  height: 100%;
  align-items: center;
  justify-content: space-around;
  margin:2% 5%;
}
.header-nav li {
  list-style: none;
  margin-left: 2vw;
  font-size: 2vw;
  color: #ffb800;
}
.header-nav a {
  text-decoration: none;
  color: #ffb800;
}
a:hover {
  color: #fd9001;
  opacity: 0.5;
}
}





@media screen and (min-width:769px) and ( max-width:1024px) {
    /*　画面サイズが769pxから1024pxまではここを読み込む　*/
  .hello p{
  width: 100vw;
  color: rgba(255, 255, 255, 0.705);
  font-family: "メイリオ", "Meiryo", sans-serif;
  font-size: 7vw;
  line-height: 8vw;
  text-align: center;
  letter-spacing: 5px;
  position: relative;
  top: 60%;
  left: 50%;
  transform: translate(-50%,-50%);
  opacity: 0;
  -webkit-animation: example 1s ease 1s 1 forwards;
  animation: example 1s ease 1s 1 forwards;
}
@-webkit-keyframes example {
  100% {
    opacity: 1;
  }
}
@keyframes example {
  100% {
    opacity: 1;
  }
}
.header-wrap {
  font-family: "メイリオ", "Meiryo", sans-serif;
  font-weight: bold;
  width: 90%;
  margin: 2% auto;
}
.header-logo {
  color: #ffb800;
  height: 50px;
  width: 30%;
  margin: 3vw 0 0 3vw ;
}
.header-logo h2 {
  font-size: 1vw;
  letter-spacing: 0.5vw;
  text-align: center;
  margin-bottom: 1vw;
}
.header-logo h1 {
  font-size: 4vw;
  letter-spacing: 0.5vw;
  text-align: center;
  margin: 0;
}
.header-nav {
  width: 80%;
  margin:4% 0 auto;
}
.header-nav ul {
  height: 50px;
  align-items: center;
  justify-content: space-between;
}
.header-nav li {
  list-style: none;
  margin-right:2%;
  font-size:2.3vw;
  color: #ffb800;
}
.header-nav a {
  text-decoration: none;
  color: #ffb800;
}
a:hover {
  color: #fd9001;
  opacity: 0.5;
}
}
</style>