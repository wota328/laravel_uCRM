<script setup>
import { Link } from '@inertiajs/inertia-vue3';
</script>

<template>
 Inertiaテストです。<br>
 <a href="/">aタグでWelcomeに移動</a><br>
 <Link :href="route('inertia.index')">LinkでWelcomeに移動</Link>
</template>