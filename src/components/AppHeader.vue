<script>

export default {
    name: "AppHeader",
    data() {
        return {
            links: [
                {
                    label: 'Characters',
                    url: '#',
                    active: false
                },
                {
                    label: 'Comics',
                    url: '#',
                    active: true
                },
                {
                    label: 'Movies',
                    url: '#',
                    active: false
                },
                {
                    label: 'TV',
                    url: '#',
                    active: false
                },
                {
                    label: 'Games',
                    url: '#',
                    active: false
                },
                {
                    label: 'Collectibles',
                    url: '#',
                    active: false
                },
                {
                    label: 'Videos',
                    url: '#',
                    active: false
                },
                {
                    label: 'Fans',
                    url: '#',
                    active: false
                },
                {
                    label: 'News',
                    url: '#',
                    active: false
                },
                {
                    label: 'Shop',
                    url: '#',
                    active: false
                },
            ]
        };
    }
}

</script>

<template>

    <header>

        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="Logo">
        </div>

        <ul>
            <li v-for="element in links"
            :class="{active: element.active == true}">
                <a :href="element.url">
                    {{ element.label }}

                </a>
            </li>

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