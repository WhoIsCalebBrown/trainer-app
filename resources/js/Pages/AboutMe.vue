<script setup>
import ContactForm from "@/Components/ContactForm.vue";
import HeaderNav from "@/Components/HeaderNav.vue";
import MyStory from "@/Components/MyStory.vue";
import {Head} from "@inertiajs/vue3";
</script>

<template>
    <Head title="About"/>
    <HeaderNav class="z-10 absolute w-full" />
    <MyStory />
    <ContactForm class="relative"/>
</template>

<style scoped>

</style>
