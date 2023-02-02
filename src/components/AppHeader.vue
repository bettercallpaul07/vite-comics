<script>

export default {
    name: "AppHeader",
}

</script>

<template>

    <header>

        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="Logo">
        </div>

        <ul>
            <li><a href="#">Characters</a></li>
            <li class="active"><a href="#">Comics</a></li>
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
    height: 10vh;

    .logo {
        padding: 10px 0px;
        height: 100%;

        img {
            width: 100%;
            height: 100%;
        }

    }
}


ul {
    display: flex;
    align-items: center;
    list-style: none;
    height: 100%;
    


    li {
        height: 100%;
        display: flex;
        align-items: center;
        color: black;
        
        a {
            text-decoration: none;
            padding: 0px 10px;
            cursor: pointer;
            text-transform: uppercase;
            font-weight: bold;
            color: black;
        }

        &.active {
            border-bottom: 3px solid blue;
            a {
                color: blue;
            }
        }
    }
}
</style>