<script setup></script>

<template>
  <div>
    <h2>내사이트</h2>
    <!-- 메뉴 -->
     <nav>
      <!-- 홈
      어바웃 -->
      <router-link to="/">홈</router-link>
      <router-link to="/about">소개</router-link>
      <router-link to="/login">로그인</router-link>
     </nav>
     <!-- 홈페이지 보여주는 곳 -->
      <RouterView></RouterView>
  </div>
</template>

<style scoped></style>
