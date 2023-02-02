<script>

export default {
    name: "AppLinks",
}

</script>

<template>

    <section>
        <div class="spec">
            <ul>
                <li><img src="../assets/img/buy-comics-digital-comics.png" alt=""><span>Digital Comics</span></li>
                <li><img src="../assets/img/buy-comics-subscriptions.png" alt=""><span>DC Merchandise</span></li>
                <li><img src="../assets/img/buy-comics-shop-locator.png" alt=""><span>Subscription</span></li>
                <li><img src="../assets/img/buy-dc-power-visa.svg" alt=""><span>Comic Shop Locator</span></li>
                <li><img src="../assets/img/buy-comics-merchandise.png" alt=""><span>DC Power Visa</span></li>
            </ul>
        </div>


    </section>



</template>

<style lang="scss" scoped>
section {
    background-color: rgba(12, 115, 233, 0.993);
    color: white;
    height: 20vh;
    display: flex;
    justify-content: center;

    .spec {
        display: flex;
        justify-content: space-around;
        align-items: center;

        ul {
            display: flex;
            align-items: center;
            list-style: none;
            text-transform: uppercase;

            li {
                padding: 0px 40px;

                img {
                    width: 50px;
                }

                span: {
                    padding: 0px 5px;

                }
            }


        }

    }




}
</style>