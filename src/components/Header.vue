<template>
    <div class="container">
        <h1>La mia prima app con Vue CLI!</h1>
    </div>
</template>

<script>
import { title } from 'process';

export default {
    name: "Title",
}
</script>

<style scoped>
.container {
    max-width: 1200px;
    margin: 0 auto;
}

.container h1 {
    color: darkblue;
    font-weight: bold;
    text-shadow: 5px #000;
}
</style>