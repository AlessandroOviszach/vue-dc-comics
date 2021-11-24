<template>

    <main>
        <div class="container">
            <h1> &#45;&#45;&#62; Content goes here &#60;&#45;&#45; </h1>
        </div>
    </main>

</template>

<script>
export default {
    name : 'Main'
}
</script>

<style scoped lang="scss">
    @import '@/Style/utilities.scss';
    @import '@/Style/variabili.scss';


    main {
        color: white;
        background-color: $black;

        h1{
            padding: 3rem 5rem;
        }
    }
</style>