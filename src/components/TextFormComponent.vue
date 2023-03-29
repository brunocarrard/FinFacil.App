<template>
    <div class="container">
        <div class="row">
            <div class="col-3">
                <label class="pb-2">{{ title }}</label>
            </div>
        </div>
        <div class="row">
            <div class="col-6">
                <input type="text">
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        props: {
            title: String
        }
    }
</script>

<style>
    .container {
        max-width: 200px;
    }
</style>