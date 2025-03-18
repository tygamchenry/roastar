<template>
    <button @click="handleClick" class="btn">{{ label }}</button>
</template>

<script>
export default {
    props: {
        label: {
            type: String,
            default: 'Click It...'
        }
    },
    methods: {
        handleClick() {
            alert('Thank you!');
        }
    }
}
</script>

<style scoped>
.btn {
    padding: 10px 15px;
    background-color: #007bff;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.btn:hover {
    background-color: #0056b3;
}
</style>