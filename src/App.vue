<template>
    <div id="app">
        <p class="test">vue-cli-test  vue-cli-test  vue-cli-test  </p>
        <p class="test">{{msg}}</p>
    </div>
</template>
<script>
    export default {
        name:'App',
        data:function(){
            return {
                msg:"hello vue1 !!"
            }
        },
    }
</script>
<style >
    .test{
        color:#020202;
        font-size:18px;
    }
</style>