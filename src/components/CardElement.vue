<script>
export default {
    name: 'CardElement',
    // Dati dall'esterno
    props: {
        title: String,
        src: String,
        series: String,
    },
    // Dati interni
    data() {
        return {
            message: 'Ciao'
        };
    }
}
</script>

<template>
    <div class="elem">

        <div>
            <img :src="src" :alt="title">
        </div>

        <h4>
            {{ title }}
        </h4>

        <p>
            {{ series }}
        </p>

    </div>
</template>

<style lang="scss" scoped>
.elem {

    padding: 10px;
    width: calc(100%/4);

    img {
        width: 100%;
    }
}
</style>