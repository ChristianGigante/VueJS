<template>
    <div id="app-2">
      <span v-bind:title="message">
        Hover your mouse over me for a few seconds
        to see my dynamically bound title!
      </span>
    </div>
</template>

<script >
export default ({
    name: 'app-2',
    data() {
        return {
            message: 'I am loading this page on ' + new Date().toLocaleString()
        }
    }
})
</script>