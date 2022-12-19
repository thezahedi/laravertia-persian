<script setup>
import AuthenticatedLayout from '@/Layouts/AuthenticatedLayout.vue';
import Card from '@/Components/Card.vue';

let props = defineProps({
    posts: Array,
});
</script>

<template>

    <Head title="Dashboard" />

    <AuthenticatedLayout>
        <template #header>
            داشبرد
        </template>

        <Card>
            <table class="w-full">
                <tr>
                    <td>
                        name
                    </td>
                    <td>
                        name
                    </td>
                    <td>
                        name
                    </td>
                </tr>
            </table>
        </Card>
    </AuthenticatedLayout>
</template>
