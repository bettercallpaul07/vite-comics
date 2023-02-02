<script>

export default {
    name: "AppHeader",
}

</script>

<template>

    <header>

        <div class="logo">
            <img src="../assets/img/favicon.ico" alt="">
        </div>

        <ul>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Collectibles</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">Fans</a></li>
            <li><a href="#">News</a></li>
            <li><a href="#">Shop</a></li>
        </ul>



    </header>



</template>

<style lang="scss" scoped>

header {
    display: flex;
    justify-content: space-around;
    align-items: center;
    min-height: 10vh;
}


ul {
    display: flex;
    list-style: none;

    li {
        padding: 5px 10px;
        cursor: pointer;
    }
}



</style>