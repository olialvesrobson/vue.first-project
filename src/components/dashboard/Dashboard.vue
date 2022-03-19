<template>
    <div class="dashboard-root">
        <img class="item-img" :src="imgURL" alt=""><br/>
        <h1>This is my first Project with Vue</h1>
    </div>
    
</template>

<script>
    export default {
        data () {
            return {
                imgURL : "https://img.freepik.com/free-vector/hand-drawn-flat-design-people-waving-illustration_23-2149195759.jpg?t=st=1647689332~exp=1647689932~hmac=fc5458ac68bd312eb2f7106e21aaf554704850471f22822bffa9b9fad2fc5f36&w=1480"
            }
        },
    }

</script>

<style>
    .dashboard-root {
        display: grid;
        padding: 10px;
        align-items: center;
        justify-content: center;
    }
    .item-img {
        width: 100%;
        height: auto;
        display: block;
        margin-left: auto;
        margin-right: auto;
        border-radius: 40px;
        margin: 5px;
    }
</style>