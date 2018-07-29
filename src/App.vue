<template>
    <div id="app">
        <img src="./images/logo.png" alt="logo"/>
        <p class="test">{{msg}}</p>
    </div>
</template>
<script>
    //    import Vue from 'vue'
    export default {
        name: 'App',
        data(){
            return {
                msg: "hello vue !!"
            }
        },
    }
</script>
<style lang="less">
    #app {
        text-align: center;
        img {
            width: 100px;
        }
    }
</style>