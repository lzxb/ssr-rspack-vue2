<template>
    <div>
        Count value:
        {{count}}
        <button @click="count++">Add</button>
    </div>
</template>
<script lang="ts" setup>
import { ref } from 'vue'

const count = ref(0)
</script>