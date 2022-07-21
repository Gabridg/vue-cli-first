<template>
    <div class="jumbotron">
        <h4>Jumbotron</h4>
    </div>
</template>

<script>
export default {
    name: "HeroComponents",
}
</script>

<style scoped>
.jumbotron {
    background-image: url('../assets/jumbotron-prova.jpg');
    background-position: center;
    background-size: contain;
    height: 400px;
}

.jumbotron h4 {
    text-align: center;
    font-size: 25px;
    color: #06e;
    line-height: 250px;
}
</style>