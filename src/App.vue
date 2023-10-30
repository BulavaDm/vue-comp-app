<template>
    <button @click="increment">
        {{ refState }}
    </button>
</template>

<script setup>
    import { ref } from 'vue'

    const refState = ref(0)

    function increment() {
        // refState.value++
    }
</script>



