<template>
  <div class="main-template">
    <div class="d-flex flex-column align-items-center">
      <div class="d-flex justify-content-center w-50">
        <img class="main-img" src="@/assets/images/main1.png" alt="main1">
        <img class="main-img" src="@/assets/images/main2.png" alt="main2">
        <img class="main-img" src="@/assets/images/main5.png" alt="main5">
        <img class="main-img" src="@/assets/images/main4.png" alt="main4">
        <img class="main-img" src="@/assets/images/main3.png" alt="main3">
      </div>
      <h1 class="main-title">싸피룰렛</h1>
      <div>
        <router-link to="/result">
          <button class="main-button btn btn-dark mr-1">시작하기</button>
        </router-link>
        <a href="https://frosty-einstein-bf8978.netlify.app/" class="main-button btn btn-warning">싸피솔덤</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MainView',
}
</script>

<style>
@font-face {
  font-family: 'SDSamliphopangche_Outline';
  src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts-20-12@1.0/SDSamliphopangche_Outline.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
@font-face {
  font-family: 'CookieRunOTF-Bold';
  src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_twelve@1.0/CookieRunOTF-Bold00.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
.main-template {
  background-color: #67D5B5;
  margin-top: 15.5%;
}
.main-img {
  width: 5%;
  margin: 0.7%;
}
.main-title {
  font-family: 'SDSamliphopangche_Outline';
  font-size: 100px;
  color: white;
}
.main-button {
  font-family: 'CookieRunOTF-Bold';
  color: white;
}
</style>