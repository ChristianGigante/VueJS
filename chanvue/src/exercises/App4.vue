<template>
    <div id="app-4">
        <ol>
            <li v-bind="todo" v-for="todo in todos">
                {{ todo.text }}
            </li>
        </ol>
    </div>
</template>

<script >
export default ({
    data() {
        return {
            todos : [
                {
                    text: 'Learn JS'
                },
                {
                    text: 'Learn Vue'
                },
                {
                    text: 'Build Something Awesome'
                }
            ]
        }
    }
})
</script>