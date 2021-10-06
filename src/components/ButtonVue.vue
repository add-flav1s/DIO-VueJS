<template>
    <button class="btn btn-lg btn-block" @click="click">
        Cliquei {{ count }} vezes.
    </button>
</template>

<script>
export default {
    name: "ButtonVue",
    data() {
        return {
            count: 0,
        };
    },
    methods: {
        click() {
            this.count++;
        },
    },
};
</script>