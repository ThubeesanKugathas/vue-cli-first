<template>
    <div class="jumbotron">
        <h1>Questa è una jumbotron!</h1>
    </div>
</template>

<script>
    export default {

    }
</script>

<style lang="scss">
    .jumbotron {
        height: 500px;
        background-image: url(../assets/banner.jpg);
        background-position: center; 
        background-repeat: no-repeat; 
        background-size: cover;
    }

    .jumbotron h1 {
        line-height: 500px;
    }
</style>