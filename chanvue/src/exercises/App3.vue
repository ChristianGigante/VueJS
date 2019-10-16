<template>
    <div id="app-3">
        <span v-if="seen">Now you see me!</span>
    </div>
</template>

<script >
export default ({
    // name: 'app-3',
    data() {
        return {
            seen : true
        }
    }
})
</script>