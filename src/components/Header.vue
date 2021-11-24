<template>
    <header>
        <!-- div di contenimento all'80% -->
        <div class="container d-flex">
            <!-- Logo section -->
            <div class="logo">
                <img src="../assets/dc-logo.png" alt="DC logo">
            </div>

            <!-- Menu section -->
            <div class="menu">
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>Tv</li>
                    <li>Games</li>
                    <li>Collectionables</li>
                    <li>Videos</li>
                    <li>Fans</li>
                    <li>News</li>
                    <li>Shop</li>
                </ul>
            </div>
        </div>
    </header>

</template>

<script>
export default {
    name : 'Header'
}
</script>

<style scoped lang="scss">
    @import '@/Style/utilities.scss';
    @import '@/Style/variabili.scss';

    header {
        display: flex;
        justify-content: space-around;
        height: 150px;

        .logo {
            width: 40%;
            display: flex;
            justify-content: center;
            img {
                padding: 1rem;
                height: 100%;
            }
        }

        .menu {
            display: flex;
            align-items: center;
            height: 100%;
            width: 60%;
            ul {
                display: flex;
                align-items: center;
                list-style: none;
                font-weight: 400;
                li {
                    padding: 0 1rem;
                    text-transform: uppercase;
                    &:hover {
                        color: $primary-color;
                    }
                }
            }
        }
    }
</style>