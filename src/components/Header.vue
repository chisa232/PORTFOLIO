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
    <!-- <div id="hamburger">
      <span></span>
      <span></span>
      <span></span>
    </div> -->
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
  width: 50vw;
  color: rgba(255, 255, 255, 0.705);
  font-family: "メイリオ", "Meiryo", sans-serif;
  font-size: 4rem;
  line-height: 6rem;
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
  display: flex;
  font-weight: bold;
  width: 80%;
  margin: 2% auto;
}
.header-logo {
  color: #ffb800;
  height: 50px;
  width: 30%;
  margin: 3vw 0 0 5vw ;
}
.header-logo h2 {
  font-size: 1rem;
  letter-spacing: 5px;
  text-align: center;
  margin-bottom: 2%;
}
.header-logo h1 {
  font-size: 2rem;
  letter-spacing: 10px;
  text-align: center;
  margin: 0;
}
.header-nav {
  width: 70%;
  margin:5% 0 auto;
}
.header-nav ul {
  display: flex;
  height: 50px;
  align-items: center;
}
.header-nav li {
  list-style: none;
  margin-right: 5%;
  font-size: 1.8rem;
  color: #ffb800;
}
.header-nav a {
  text-decoration: none;
  color: #ffb800;
}
a:hover {
  color: #fd9001;
  opacity: 0.9;
}

@media screen and(max-width:768px) {
}
</style>