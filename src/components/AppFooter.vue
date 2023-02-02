<script>

export default {
    name: "AppFooter",
}

</script>

<template>

    <footer>
        <div class="h-footer">

        </div>
        <div class="l-footer">
            SIGN UP
        </div>
    </footer>




</template>

<style lang="scss" scoped>

footer {

    .h-footer {
        background-image: url(../assets/img/footer-bg.jpg);
        min-height: 45vh;
        background-repeat: no-repeat;
        background-size: cover;
    }

    .l-footer {
        background-color: grey;
        min-height: 10vh;
    }


    }

</style>