<script setup>
import { ref} from 'vue';

const msg = ref('Vue 3');
</script>

<template>
<h1 class="heading-1">Hello World! from, {{msg}}</h1>
</template>

<style scoped>
.heading-1 {
    color: orangered;

}

</style>