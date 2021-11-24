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
                    <li> <a href="#"> Characters </a> </li>
                    <li> <a href="#"> Comics </a> </li>
                    <li> <a href="#"> Movies </a> </li>
                    <li> <a href="#"> Tv </a> </li>
                    <li> <a href="#"> Games </a> </li>
                    <li> <a href="#"> Collectionables </a> </li>
                    <li> <a href="#"> Videos </a> </li>
                    <li> <a href="#"> Fans </a> </li>
                    <li> <a href="#"> Shop </a> </li>
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
        height: 120px;

        .logo {
            width: 40%;
            display: flex;
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
                height: 100%;

                li {
                    padding: 0 1rem;
                    text-transform: uppercase;

                    a {
                        text-decoration: none;
                        color: currentColor;
                        &:hover,
                        &:active {
                            cursor: pointer;
                            color: $primary-color;
                        }
                    }
                }
            }
        }
    }
</style>