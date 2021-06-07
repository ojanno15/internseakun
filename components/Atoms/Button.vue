<template>
    <div>
        <button @click="$emit('anotherPage')" type="button" class="button">
        {{ name }}
        </button>
    </div>
</template>

<script>
export default {
    props: {
        name: '',
    }
}
</script>

<style>
.button {
    width: 80px;
    height: 30px;
    border-radius: 5px;
    background-color: black;
    text-align: center;
    margin-left: 150px;
    color: white;
    cursor: pointer;
}
</style>