<template>
    <div class="column is-4 py-6 is-flex is-align-items-start">
        <span
            class="is-flex-shrink-0 mr-6 is-inline-flex is-justify-content-center is-align-items-center has-background-primary has-text-white"
            style="width: 48px; height: 48px; border-radius: 100%;">1</span>
        <p class="is-size-6 has-text-grey-dark">
            {{ props.text }}
        </p>
    </div>
</template>

<script setup lang="ts">
const props = defineProps<{ text: string }>()
</script>