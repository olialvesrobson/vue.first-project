<template>
    <div class="main-root">
        <img class="header-img" src="../../assets/logo.svg" alt="">
        <div class="card">
            <span class="title">
                Hi my name is Robson
            </span>
            <p class="content">
                As a self-motivated and reliable professional with 10+ years of experience, Robson is passionate about delivering valuable outcomes fostering a culture of continuous technical learning and improvement within the organisation and personnel.
            </p>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style>
    .main-root {
        display: flex;
        padding: 10px;
        margin: 10px;
        align-items: center;
        justify-content: center;
    }
    .header-img {
        width: auto;
        height: 50px;
        border-radius: 25px;
    }
    .card {
        display: grid;
        padding: 10px;
        margin: 10px;
        border-radius: 20px;
        border-width: 1px;
        border-color: #c3c3c3;
        border-style: inset;
    }
    .title {
        font-weight: bold;
        font-size: x-large;
        padding: 10px;
        border-bottom-width: 1px;
        border-bottom-color: #cecece;
        text-decoration: none;
        color: hsla(160, 100%, 37%, 1);
        transition: 0.4s;
    }
    .content {
        padding: 10px;
    }
</style>