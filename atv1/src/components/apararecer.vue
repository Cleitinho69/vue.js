<template>
    <div id="telaSecundaria">
        <p> {{ txt }} </p>
    </div>
</template>

<script>
    export default {
        name: 'aparecerTela',
        props:{
            txt: String
        }
    }
</script>

<style scoped>
    #telaSecundaria{
        border-radius: 20px;

        margin-top: 20px;

        width: 150px;
        height: 150px;

        background-color: #ffffff;

        display: flex;
        flex-wrap: wrap;
    }

    p{
        word-wrap:normal;
        font-size: 30px;
    }
</style>