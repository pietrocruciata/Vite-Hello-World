<script>
export default {
    data() {
        return {
            message: 'La mia prima app con vite'
        }
    }
}
</script>

<template>
    <div>

        <h1 class="center">
            {{ message }}
        </h1>
    </div>

</template>

<style>
.center {
    text-align: center;
}
</style>