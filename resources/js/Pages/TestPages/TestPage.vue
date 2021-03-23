<template>
    <app-layout>
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 leading-tight">
                Test Page Redirection
            </h2>
        </template>
    </app-layout>
</template>
<script>
import AppLayout from '@/Layouts/AppLayout'
export default {
    components: {
        AppLayout
    },
    mounted() {
        console.log('TestPage Component');
    }
}
</script>