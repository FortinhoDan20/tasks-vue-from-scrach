<template>
    <button @click="getClick()" :style="{ background: color }" class="btn" > {{ text}} </button>
</template>

<script>
export default {
    name: "Buttom",
    props: {
        text: String,
        color: String
    },
    methods: {
        getClick() {
            console.log('click')
        }
    }
}

</script>

<style scoped>

</style>