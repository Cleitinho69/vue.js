<template>
    <div :class="['center','column']">
        <form action="">
            <input type="text" v-model="txt" key="txt" wrap="hard" />
        </form>
        <apararecer :txt="txt"/>
    </div>
</template>

<script>

import apararecer from './apararecer.vue';

export default {
    name: 'escreverTela',
    data() {
        return {
            txt: ''
        }
    },
    components: {
        apararecer
    }
}
</script>

<style scoped>
    input{
        border-radius: 20px;
        height: 30px;
    }
</style>