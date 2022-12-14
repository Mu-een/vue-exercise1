<template>
    <div>
<NavBar />
<ContactForm />
    </div>
</template>

<script>
import NavBar from '@/components/NavBar.vue'
import ContactForm from '@/components/ContactForm.vue'
    export default {
        name: 'ContactView',
        components: {
            NavBar,
            ContactForm
        }
    }
</script>

<style scoped>

</style>