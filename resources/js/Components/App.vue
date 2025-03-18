<!-- resources/js/components/App.vue -->
<template>
    <div>
        <h1>Tyga's Simple Vue Button Component</h1>
        <MyButton label="Please Click Me!" />
    </div>
</template>

<script>
import MyButton from './ProjectButton.vue';

export default {
    components: {
        MyButton
    }
}
</script>

<style>
h1 {
    color: #333;
    font-weight: bold;
}
</style>