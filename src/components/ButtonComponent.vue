<template>
    <button @click="$emit('clicked')">
        <span>{{ title }}</span>
    </button>
</template>

<script>
    export default {
        props: {
            title: String
        }
    }
</script>