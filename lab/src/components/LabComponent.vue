<template>
    <div>
        {{ message }}<br />
        <button type="button" @click="showLog">Here's a button that show up a console log, check it out!</button>
    </div>
</template>

<script setup>
const message = 'This is my custom component just created!';
function showLog() {
    console.log('Hello World!');
}
</script>

<style lang="scss" scoped>

</style>