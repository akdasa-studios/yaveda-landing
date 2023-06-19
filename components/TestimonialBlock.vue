<template>
    <div class="column is-4">
        <div class="box p-6">
            <p class="is-size-6 mb-10">
                {{ props.text }}
            </p>
            <!-- <img class="mb-6 is-cover" style="width: 48px; height: 48px; object-position: top; border-radius: 100%;"
                src="https://images.unsplash.com/photo-1544717305-2782549b5136?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=334&amp;q=80"
                alt=""> -->
            <!-- <p class="mb-2 title is-4">Иван</p> -->
            <p class="has-text-grey-dark">Иван</p>
        </div>
    </div>
</template>

<script setup lang="ts">
const props = defineProps<{text: string}>()
</script>