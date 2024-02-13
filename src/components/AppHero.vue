<script>
export default {
    data() {
        return {
            title: 'Ciao!',
            text: 'Questa è la mia app!'
        };
    },
};
</script>

<template>
    <div class="jumbotron">
        <h1>{{ title }}</h1>
        <p>{{ text }}</p>

    </div>
</template>

<style>
.jumbotron {
    background-color: #ccc;
    padding: 20px;
    text-align: center;
    border-radius: 5px;
}
</style>