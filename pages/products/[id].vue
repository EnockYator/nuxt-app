<template>
    <div>
        <h1>Product Details for {{id}}</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. At labore voluptatem
            dicta, obcaecati possimus illum vel adipisci harum earum iure.
        </p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. At labore voluptatem
            dicta, obcaecati possimus illum vel adipisci harum earum iure.
        </p>
    </div>
</template>

<script setup>
const {id} = useRoute().params;

definePageMeta ({
    layout: 'products'
});
</script>

<style scoped>


</style>