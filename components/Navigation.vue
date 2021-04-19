<template>
<div class="container-fluid sticky-top bg-white">
    <div class="container">
         <nuxt-link to="" class="item-nav">DANH MỤC SẢN PHẨM <i class="fa fa-angle-down"></i></nuxt-link>
         <nuxt-link to="" class="item-nav">TƯ VẤN THIẾT KẾ NỘI THẤT <i class="fa fa-angle-down"></i></nuxt-link>
         <nuxt-link to="" class="item-nav">CẨM NANG NỘI THẤT</nuxt-link>
         <nuxt-link to="" class="item-nav">ĐỐI TÁC THI CÔNG</nuxt-link>
         <nuxt-link to="" class="item-nav">ĐỐI TÁC TÀI CHÍNH</nuxt-link>
    </div>
</div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.container-fluid{
  border-bottom: 0.1px solid  #d4d4d4;
}
.container{
  padding: 20px 50px;
  display: flex;
  justify-content: space-around;
  font-weight: bold;
}
.item-nav{
    text-decoration: none;
    color: #070404;
    font-family: 'Roboto Condensed';
    letter-spacing: 1px;
    transition: 0.2s;
}

.item-nav:hover{
 color: rgb(0, 132, 255);
}
</style>