<template>
    <div>
<NavBar />
<Products />
    </div>
</template>

<script>
import NavBar from '@/components/NavBar.vue'
import Products from '@/components/Products.vue'
    export default {
        name: 'ProductsView',
        components: {
            NavBar,
            Products
        }
    }
</script>

<style scoped>

</style>