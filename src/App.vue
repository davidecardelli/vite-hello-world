<script>
import AppTitle from './components/AppTitle.vue';
import AppJumbo from './components/AppJumbo.vue';

export default {
    data() {
        return {

        }
    },
    components: {
        AppTitle,
        AppJumbo,
    },
}

</script>

<template>

    <div class="container">
        <app-title></app-title>
        <app-jumbo></app-jumbo>
    </div>

</template>

<style>
.container {
    max-width: 1200px;
    margin: 0 auto;
}
</style>

