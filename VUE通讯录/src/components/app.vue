<template>
    <div id="contain">  
        <h1>通 义 达</h1>
        <h2>西安通义达电子科技服务有限公司</h2>
        <div class="btns">
            <router-link to="/home/register" class="btn">注册</router-link>
            <router-link to="/home/login">登录</router-link>
        </div>
        <router-view></router-view> 
    </div>
</template>  

<style scoped>
@import '../assets/css/app.css'
</style>