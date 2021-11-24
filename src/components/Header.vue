<template>
    <header class="container">
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


    </header>

</template>

<script>
export default {
    name : 'Header'
}
</script>

<style scoped lang="scss">
    .container {
        background-color: #2c3e50;;
        display: flex;
        align-items: center;
        height: 100px;

        .logo {
            display: flex;
            justify-content: center;
            width: 45%;
            padding: 1rem;
            
            img {
            height: 100%;
            }
        }


        .menu {
            height: 100%;
            background-color: tomato;
            ul {
                display: flex;
                align-items: center;
                list-style: none;
                li {
                    height: 100%;
                    text-transform: uppercase;
                }
            }
        }
    }
</style>